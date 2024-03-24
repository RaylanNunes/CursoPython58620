# CursoPython58620
Pipeline de Dados: Documentação do Projeto

Visão Geral

Este projeto visa construir um pipeline de dados completo para coletar, processar, armazenar e disponibilizar dados de bancos brasileiros. O pipeline consiste em várias etapas, incluindo extração de dados de uma API, tratamento dos dados, armazenamento em um banco de dados SQL Server e implementação de um sistema de alerta em caso de falhas.

Etapas do Pipeline

1. Extração de Dados

Nesta etapa, os dados são obtidos de uma API pública que fornece informações sobre bancos brasileiros.

URL da API: https://brasilapi.com.br/api/banks/v1

Biblioteca utilizada: requests

2. Tratamento de Dados

Os dados extraídos da API são tratados para garantir consistência e qualidade antes de serem armazenados no banco de dados.

Tratamento de valores ausentes
Remoção de duplicatas
Conversão para DataFrame

Bibliotecas utilizadas: pandas

3. Armazenamento de Dados

Os dados tratados são armazenados em um banco de dados SQL Server para posterior análise e consulta.

Banco de dados: SQL Server

Biblioteca utilizada: pyodbc

Nome da tabela: Bancos

4. Sistema de Alerta

Implementação de um sistema de alerta para notificar em caso de falhas durante o processo de extração de dados da API.

Biblioteca utilizada: plyer

Requisitos de Configuração

É necessário configurar um ambiente virtual para o projeto.

Os pacotes necessários estão listados no arquivo requirements.txt.

Fluxo de Execução

Ativar o ambiente virtual.

Instalar as dependências listadas no arquivo requirements.txt.

Executar o script pipeline.py.

O script realizará as etapas do pipeline conforme descrito acima.


GitHub Repository

O código fonte do projeto está disponível em https://github.com/RaylanNunes/CursoPython58620/blob/main/Entrega_Final.ipynb
