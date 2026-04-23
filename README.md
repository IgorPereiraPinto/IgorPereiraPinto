# Igor Pereira — Senior Data & BI Analyst

**Transformo dados comerciais em decisões.** 10+ anos atuando na interseção 
entre dados e negócio — de operações (BPO) a planejamento comercial 
(vendas, metas e comissionamento).

O que me diferencia: não entrego só dashboard, entrego o diagnóstico. 
Sei perguntar "por que o resultado caiu?" antes de abrir qualquer ferramenta.

📫 [LinkedIn](https://www.linkedin.com/in/igorpereirapinto/) · 
[E-mail](mailto:letrasigor@yahoo.com.br) · 
[Portfólio](https://sites.google.com/view/portfolio-de-projetos/home)

---

## Tech Stack

![Power BI](https://img.shields.io/badge/Power_BI-F2C811?style=for-the-badge&logo=powerbi&logoColor=black)
![DAX](https://img.shields.io/badge/DAX-F2C811?style=for-the-badge&logo=powerbi&logoColor=black)
![SQL Server](https://img.shields.io/badge/SQL_Server-CC2927?style=for-the-badge&logo=microsoftsqlserver&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-150458?style=for-the-badge&logo=pandas&logoColor=white)
![Excel](https://img.shields.io/badge/Excel-217346?style=for-the-badge&logo=microsoftexcel&logoColor=white)
![AWS](https://img.shields.io/badge/AWS-232F3E?style=for-the-badge&logo=amazonaws&logoColor=white)
![Azure](https://img.shields.io/badge/Azure-0078D4?style=for-the-badge&logo=microsoftazure&logoColor=white)
![Power Automate](https://img.shields.io/badge/Power_Automate-0066FF?style=for-the-badge&logo=powerautomate&logoColor=white)
![Salesforce](https://img.shields.io/badge/Salesforce-00A1E0?style=for-the-badge&logo=salesforce&logoColor=white)

---

## Projetos em Destaque

---

### 💳 Análise de Crédito — Case End-to-End (Python + SQL Server + Power BI + Web Dashboard)
Case técnico focado na construção de uma visão analítica para concessão e monitoramento de crédito, com análise de risco, inadimplência e perfil de clientes para apoio à tomada de decisão.

Pipeline: Base de dados de crédito (clientes, operações e comportamento de pagamento) → ETL em Python (tratamento, padronização e validação dos dados) → Modelagem em SQL Server (estrutura analítica para análise de carteira e risco) → Dashboard Web interativo (HTML + CSS + JS) com visão executiva de concessão, inadimplência e distribuição de risco.

Análises: Volume de crédito concedido · Taxa de inadimplência · Distribuição por faixa de risco · Perfil de clientes · Concentração de exposição por segmento.

Repositório  
[Dashboard](https://igorpereirapinto.github.io/analise_de_credito)

---

### 📈 Planejamento Comercial — Case End-to-End (Python + SQL Server + Power BI + Power Automate)

Pipeline de dados ponta a ponta para análise de performance comercial, 
forecast e budget. Consolida 6 fontes Excel em um star schema no SQL Server, 
com monitoramento executivo em Power BI, automações via Power Automate e 
apresentação de resultados em HTML.

**Pipeline:** Excel (vendas + dimensões + metas) → ETL Python 7 etapas com 
dupla validação (4 testes RAW + 7 testes STAGING) → Star schema Kimball no 
SQL Server (2 fatos + 8 dimensões, colunas PERSISTED) → Dashboard Power BI 
(20+ medidas DAX, RLS por gerente) → 5 fluxos Power Automate → Apresentação 
executiva HTML (14 slides self-contained).

**Escala:** ~20.004 transações · 528 metas · 4 anos · 11 vendedores · 
47 testes automatizados (pytest).

[Repositório](https://github.com/IgorPereiraPinto/commercial-planning-control-tower)

---

### 🏆 Procurement Analytics — Case End-to-End (Python + SQL Server + Power BI + Power Automate)

Case técnico completo simulando um problema real de Procurement: 
visibilidade sobre onde o gasto realizado diverge do planejado e por quê.

**Pipeline:** Excel → ETL em Python (7 scripts modulares, validações 
automáticas) → Modelagem em SQL Server (arquitetura medallion + star schema) 
→ Dashboard executivo no Power BI (5 páginas analíticas, IA generativa + 
Machine Learning nativos) → Automação de ingestão e alertas no Power Automate.

**Resultado:** R$ 1,80 Mi planejado · R$ 1,71 Mi realizado · 95,3% de 
atingimento · Desvio de -R$ 83,8 Mil identificado e decomposto por 
categoria, SKU e fornecedor.

[Repositório](https://github.com/IgorPereiraPinto/procurement-analytics)

---

### 📊 KPIs de Vendas — Power BI (SQL Server + DAX)

Dashboard com KPIs calculados em DAX a partir de dados do SQL Server, 
com RLS dinâmico por regional/gerência e documentação executiva.

[Repositório](https://github.com/IgorPereiraPinto/KPIs_Vendas_PowerBi) · 
[Dashboard Interativo](https://app.powerbi.com/view?r=eyJrIjoiYTQxZmIzNjYtZmM5NC00OTA2LTkxMGUtNGNhNWZhYzlhODZjIiwidCI6ImEyZGZjMjU0LWIyY2MtNDFkNC05ODBmLTg2OTgxNmYxZjkzZCIsImMiOjN9)

### 🗄️ KPIs de Vendas — SQL Server (Pipeline ETL/ELT)

Pipeline completo Raw → Staging → DW → Marts com checks de qualidade 
e queries analíticas. Complementa o projeto acima mostrando a camada 
de dados que sustenta o BI.

[Repositório](https://github.com/IgorPereiraPinto/KPIs_Vendas_SQL)

---

### 🔬 Deep Dive Analyses — Python + SQL Server

4 análises avançadas que vão além do dashboard: **Coorte** (retenção por 
safra), **Pareto ABC** (concentração de receita), **Ad Hoc** (exploratória 
com correlação) e **Real vs Forecast** (decomposição de causa raiz em 
volume/preço). Cada uma parte de uma pergunta de negócio e entrega 
diagnóstico com ação.

[Repositório](https://github.com/IgorPereiraPinto/deep-dive-analyses_v2)

---

### 🛣️ Smart Highway Analytics — Dashboard Web (BI replicável no Power BI)

Dashboard em **HTML + CSS + JS** para visão executiva e operacional de 
tráfego: KPIs, rotas, tempo de viagem, clima (demo), comparativos de 
período e páginas por área com **glossário detalhado** (definições, 
cálculo e impacto).

[Repositório](https://github.com/IgorPereiraPinto/smart-highway-analytics) · 
[Dashboard (GitHub Pages)](https://igorpereirapinto.github.io/smart-highway-analytics/)

### ⚙️ Automação de Indicadores Macro — API Banco Central → Excel

Script Python que coleta séries da API SGS do Banco Central (dólar, euro, 
Selic, IPCA), trata duplicidades e atualiza planilha automaticamente 
com agendamento diário.

[Repositório](https://github.com/IgorPereiraPinto/bcb-api-excel-automation)

---

> **Todos os repositórios:** [github.com/IgorPereiraPinto](https://github.com/IgorPereiraPinto?tab=repositories)

---

## Meu Método

Toda análise começa com uma pergunta de negócio, não com uma tabela de dados.
