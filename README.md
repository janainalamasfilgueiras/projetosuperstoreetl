
Ficha Técnica do Projeto no GitHub
Título do Projeto
Projeto de Exploração: Estrutura de Dados
Objetivo Geral
O objetivo deste projeto é construir, através do processo de ETL (Extrair, Transformar e Carregar), um sistema tabular relacional com tabelas de fatos e dimensões. Este sistema permitirá armazenar e consultar dados de forma eficiente, auxiliando a Super Store na tomada de decisões estratégicas ao gerenciar grandes volumes de dados dispersos.
Tecnologias e Ferramentas
Plataformas: Google BigQuery, Planilhas Google, Google Colab, GitHub
Linguagens: SQL (BigQuery), Python (Google Colab)
Ferramentas de Design (Opcional): LucidApp, DbSchema, drawSQL ou Power BI
Insumos
Dataset de vendas da Super Store (disponível por download via link no material do projeto). https://drive.google.com/file/d/1NhLNS49u-c4rEQUHXXTHOWPTBTWMPj9S/view
Uma tabela com dados de concorrentes, a ser criada por meio de web scraping de uma página da Wikipedia.https://en.wikipedia.org/wiki/List_of_supermarket_chains 
Metodologia (Processo ETL)
1. Extração (Extract)
Extrair dados do dataset da Super Store.
Extrair dados de concorrentes de uma fonte externa (web scraping).
2. Transformação (Transform)
Limpeza e Preparação dos Dados:
Identificar e tratar valores nulos, duplicados e inconsistências em variáveis categóricas e numéricas.
Padronizar dados (ex: converter para letras minúsculas ou maiúsculas).
Modelagem de Dados:
Projetar a estrutura da base de dados, definindo quais tabelas serão de fatos e quais serão de dimensões.
Aplicar conceitos de Star Schema ou Snowflake Schema.
Utilizar IDs existentes ou criar novos para as tabelas de dimensões.
3. Carga (Load)
Criar as tabelas de fatos e dimensões no BigQuery.
Simplificar a tabela de fatos utilizando apenas os IDs das tabelas de dimensão e as métricas de vendas relevantes.
Projetar um pipeline de dados para agendar atualizações das tabelas, considerando a ordem de dependência entre elas.
Critérios de Aceitação
Criação das tabelas de fatos e dimensões para organizar os dados.
Criação de uma Ficha Técnica (como esta) detalhando o processo de tomada de decisão e os recursos utilizados.
Upload do projeto completo no seu repositório/portfólio no GitHub.
Compartilhamento do link do repositório na plataforma.
Gravação e compartilhamento de um vídeo de no máximo 5 minutos explicando como os dados foram organizados.
Marco 3: Aprofundamento (AWS)
Após a conclusão deste projeto, o próximo passo é aprofundar os conhecimentos em computação em nuvem e engenharia de dados, completando as seguintes rotas de aprendizagem na plataforma da AWS:
AWS Essentials: Focada nos conceitos fundamentais da AWS.
Engenharia de Dados: Introdução aos conceitos de analytics, data lakes, data warehouses e ferramentas da AWS para gestão de dados.
Resultados:
https://lucid.app/lucidchart/a6909558-2b0d-4c4c-8eb7-b0e59140b355/edit?viewport_loc=-701%2C-193%2C3632%2C1733%2C0_0&invitationId=inv_f2af6249-ae6d-4456-acaf-caa618d574cd 
https://www.loom.com/share/f5fc917528ab45958622cee839cff6b4?sid=0bbf3692-db9f-485a-86fd-c99ddbecc9dd
https://docs.google.com/presentation/d/11FQbF8rlRYTIq0et8IYo7r_Z0conO_v-/edit?usp=sharing&ouid=110264823644213357807&rtpof=true&sd=true
