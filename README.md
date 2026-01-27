<h1 align="center">🔥 Felipe Costa</h1>

<p align="center">
Dev Jr (Backend/Data) • Python & Java • Automação • Ecommerce • APIs, Bancos de Dados, CI/CD & BI
</p>

---

## 👋 Sobre mim

Sou estudante de Ciência da Computação (7º período) e estou iniciando minha carreira como dev com foco em **backend e dados**.  
Gosto de estar perto do código, entender o problema de negócio e transformar isso em solução funcionando de ponta a ponta.

Hoje trabalho principalmente com:

- **Backend / APIs:** Python (FastAPI, Streamlit), Java Web (Servlets/JSP)
- **Bancos de dados:** PostgreSQL, MySQL, SQLAlchemy, Redis
- **Dados / BI:** Pandas, Power BI
- **DevOps:** Docker, Docker Compose, GitHub Actions, CI/CD
- **Integrações:** Amazon SP-API / PA-API, eBay Browse API

---

## 🛠️ Tecnologias que uso no dia a dia

### 💻 Programação & Backend

![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![Java](https://img.shields.io/badge/Java-007396?style=for-the-badge&logo=openjdk&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=for-the-badge&logo=fastapi&logoColor=white)
![Streamlit](https://img.shields.io/badge/Streamlit-FF4B4B?style=for-the-badge&logo=streamlit&logoColor=white)

### 🗄️ Bancos de dados & Cache

![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=for-the-badge&logo=postgresql&logoColor=white)
![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=for-the-badge&logo=mysql&logoColor=white)
![SQLite](https://img.shields.io/badge/SQLite-003B57?style=for-the-badge&logo=sqlite&logoColor=white)
![Redis](https://img.shields.io/badge/Redis-DC382D?style=for-the-badge&logo=redis&logoColor=white)

### 📊 Dados & BI

![Pandas](https://img.shields.io/badge/Pandas-150458?style=for-the-badge&logo=pandas&logoColor=white)
![Power BI](https://img.shields.io/badge/Power%20BI-F2C811?style=for-the-badge&logo=Power%20BI&logoColor=black)

### ☁️ DevOps & Cloud

![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)
![Docker Compose](https://img.shields.io/badge/Docker%20Compose-2496ED?style=for-the-badge&logo=docker&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub%20Actions-2088FF?style=for-the-badge&logo=githubactions&logoColor=white)
![AWS](https://img.shields.io/badge/AWS-232F3E?style=for-the-badge&logo=amazon-aws&logoColor=white)
![Render](https://img.shields.io/badge/Render-00979D?style=for-the-badge&logo=render&logoColor=white)

### 🧰 Ferramentas

![VS Code](https://img.shields.io/badge/VS%20Code-007ACC?style=for-the-badge&logo=visualstudiocode&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white)
![GitHub](https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white)
![Windows Terminal](https://img.shields.io/badge/Windows%20Terminal-4D4D4D?style=for-the-badge&logo=windows-terminal&logoColor=white)
![PowerShell](https://img.shields.io/badge/PowerShell-5391FE?style=for-the-badge&logo=powershell&logoColor=white)

---

## 📂 Projetos em destaque

### 🛒 MinerEcom – Minerador de produtos Amazon ↔ eBay  
[🔗 Repositório](https://github.com/FelipeAGCosta/miner-ecom)

Aplicação web em **Python + Streamlit** para pesquisa e análise de oportunidades de arbitragem entre **eBay** e **Amazon.com**.  
O usuário define filtros avançados (categoria, faixa de preço, condição, estoque mínimo, tipo de oferta na Amazon, vendas mensais estimadas etc.) e o sistema:

- minera produtos na **Amazon** e enriquece com preço, vendas mensais estimadas, BSR, marca, GTIN e demais atributos;
- cruza com a **eBay Browse API** para encontrar o mesmo produto via GTIN/ASIN/título;
- estima demanda usando **BSR (Best Sellers Rank)** e uma heurística de vendas aproximadas no último mês;
- retorna apenas itens que atendem simultaneamente aos filtros de eBay e Amazon, prontos para análise de arbitragem.

**Stack:** Python · Streamlit · MySQL · SQLAlchemy · Pandas · Redis · Docker · eBay Browse API · Amazon Selling Partner API (SP-API) · AWS IAM · OAuth2/LWA · Assinatura AWS SigV4

---

### 🔁 API com CI/CD – FastAPI + Docker + GitHub Actions + Postgres  
[🔗 Repositório](https://github.com/FelipeAGCosta/CI-CD-Fastapi-Demo)

Mini-projeto para treinar **pipeline de CI/CD** na prática:

- API REST em **FastAPI** com CRUD de pedidos (POST/GET/PATCH/DELETE) e documentação automática (Swagger/OpenAPI).
- Testes automatizados com **pytest** + relatório de cobertura (**pytest-cov**).
- Lint / quality gate com **ruff** (falha a pipeline se não estiver ok).
- Banco de dados **PostgreSQL** com **SQLAlchemy + Alembic** (ORM + migrations).
- Container Docker com build reproduzível.
- Pipeline de **GitHub Actions** rodando a cada push/PR (instala dependências, roda testes, builda a imagem).
- Deploy em produção no **Render**, com variáveis de ambiente e Postgres gerenciado.

---

### 📊 Dashboard de Vendas – Kaggle → PostgreSQL → Power BI  
[🔗 Repositório](https://github.com/FelipeAGCosta/Dashboard-Vendas-Powerbi-Postgres)

Projeto de Analytics/BI usando o dataset **Online Retail (Kaggle)**:

- CSV do Kaggle carregado em um banco **PostgreSQL 16** (via Docker Compose).
- Modelagem da camada de dados com SQL (schema, tabelas e views de apoio).
- Views específicas para consumo no BI (ex.: `fato_vendas`, `vendas_validas`, `resumo_qualidade_dados`).
- Conexão direta do **Power BI** no Postgres.

Dashboard com:

- **KPIs:** faturamento total, número de pedidos, clientes únicos, ticket médio;
- **Gráficos:** faturamento por mês, top 10 países por faturamento, top 10 produtos;
- **Filtros:** por período e país;
- **Qualidade de dados:** cards com taxa de registros descartados/cancelamentos.

**Stack:** PostgreSQL · Docker/Docker Compose · SQL · Power BI · DAX

---

### 🎬 Catálogo de Mídias – Java Web (Projeto acadêmico)  
[🔗 Repositório](https://github.com/FelipeAGCosta/Catalogo-Midias)

Projeto acadêmico em **Java Web** para cadastro e gerenciamento de mídias (filmes/séries/livros):

- CRUD completo com listagem, filtros e paginação.
- Implementação com **Servlets + JSP/JSTL**, padrão MVC simples.
- Acesso a dados com **JDBC** e `PreparedStatement`.
- Banco de dados **MySQL**, build com **Maven** e deploy em **Tomcat**.

---

## 📫 Contato

- 💼 LinkedIn: [Felipe Augusto Gonçalves da Costa](https://www.linkedin.com/in/felipe-augusto-gonçalves-da-costa-236462183/)
- 📧 E-mail: **felipeagcosta@hotmail.com**
