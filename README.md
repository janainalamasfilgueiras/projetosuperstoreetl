# Projeto de Exploração: Estrutura de Dados (Super Store ETL)

## 🎯 Objetivo Geral
Construir, através do processo de **ETL** (Extrair, Transformar e Carregar), um sistema tabular relacional com tabelas de **fatos** e **dimensões**.  
Esse sistema permitirá armazenar e consultar dados de forma eficiente, auxiliando a Super Store na **tomada de decisões estratégicas** ao gerenciar grandes volumes de dados dispersos.

---

## 🛠️ Tecnologias e Ferramentas
- **Plataformas:** Google BigQuery, Planilhas Google, Google Colab, GitHub
- **Linguagens:** SQL (BigQuery), Python (Google Colab)
- **Ferramentas de Design (Opcional):** LucidApp, DbSchema, drawSQL, Power BI

---

## 📂 Insumos
- **Dataset:** Vendas da Super Store  
  🔗 [Baixar Dataset](https://drive.google.com/file/d/1NhLNS49u-c4rEQUHXXTHOWPTBTWMPj9S/view)  
- **Concorrentes:** Web scraping de supermercado  
  🔗 [Página da Wikipedia](https://en.wikipedia.org/wiki/List_of_supermarket_chains)

---

## 🔄 Metodologia (Processo ETL)

### 1️⃣ Extração (Extract)
- Extrair dados do dataset da Super Store.
- Extrair dados de concorrentes de uma fonte externa (web scraping).

### 2️⃣ Transformação (Transform)
**Limpeza e Preparação dos Dados:**
- Identificar e tratar valores nulos, duplicados e inconsistências.
- Padronizar dados (ex.: minúsculas/maiúsculas).

**Modelagem de Dados:**
- Definir tabelas de fatos e dimensões.
- Aplicar **Star Schema** ou **Snowflake Schema**.
- Criar/usar IDs para dimensões.

### 3️⃣ Carga (Load)
- Criar tabelas no BigQuery.
- Simplificar a tabela de fatos com apenas IDs das dimensões e métricas relevantes.
- Projetar pipeline de atualização.

---

## ✅ Critérios de Aceitação
- Criação de tabelas de fatos e dimensões.
- Ficha Técnica documentada (este arquivo).
- Upload no GitHub.
- Compartilhamento do link na plataforma.
- Vídeo de até 5 minutos explicando a organização dos dados.

---

## 📌 Marco 3: Aprofundamento (AWS)
Após a conclusão deste projeto, o próximo passo será aprofundar os conhecimentos em computação em nuvem e engenharia de dados com:
- **AWS Essentials** (conceitos fundamentais)
- **Engenharia de Dados AWS** (analytics, data lakes, data warehouses)

---

## 📊 Resultados
- **Modelo no Lucidchart:** [Abrir Link](https://lucid.app/lucidchart/a6909558-2b0d-4c4c-8eb7-b0e59140b355/edit?viewport_loc=-701%2C-193%2C3632%2C1733%2C0_0&invitationId=inv_f2af6249-ae6d-4456-acaf-caa618d574cd)
- **Vídeo Explicativo:** [Assistir no Loom](https://www.loom.com/share/f5fc917528ab45958622cee839cff6b4?sid=0bbf3692-db9f-485a-86fd-c99ddbecc9dd)
- **Apresentação:** [Google Slides](https://docs.google.com/presentation/d/11FQbF8rlRYTIq0et8IYo7r_Z0conO_v-/edit?usp=sharing&ouid=110264823644213357807&rtpof=true&sd=true)
