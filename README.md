<h1 align="center">Hi! I'm Luiz Silva • Data Engineering</h1>

<p align="center">
  <em>Data pipelines, from source to database.</em>
</p>

<div align="center">
  <img src="https://skillicons.dev/icons?i=python,postgres,docker,django,cs,dotnet,githubactions,git,linux&theme=dark" />
</div>

---

### 👨‍💻 About

I'm Luiz Silva, a Data Engineer coming from backend development. I build batch data pipelines with Python, SQL, PostgreSQL and Apache Airflow, with a focus on data quality, testing and reproducibility. I have professional experience developing REST APIs and working with PostgreSQL databases at Minsait.

---

### 📌 Featured Projects

- 🔄 [**DataFlow Pipeline**](https://github.com/luizsoc/dataflow-pipeline)  
  Batch ELT pipeline that turns ~1.07 million raw retail transactions (UCI Online Retail II) into a tested, analytics-ready star schema in PostgreSQL, orchestrated by Apache Airflow 3 and running end to end with a single `docker compose up`.
  - **Medallion Architecture:** Bronze (raw), Silver (cleaned with Pandas) and Gold (star schema built in SQL)
  - **Data quality gates:** 13 checks per run, 11 of them blocking; 46k invalid rows quarantined, each with a reason
  - **Idempotent and auditable:** re-runs change 0 rows, and every task and check is logged in an `audit` schema
  - **Tested:** 79 unit and integration tests, run in CI with GitHub Actions on every push and pull request
  - **Stack:** Python · Pandas · SQL · PostgreSQL · Apache Airflow · Docker · GitHub Actions

- 🎮 [**GameHub**](https://github.com/luizsoc/GameHub)  
  Real-time chat platform for gamer communities, built with C#/.NET, PostgreSQL, SignalR and Docker.

---

### 🧰 Skills

- **Data Engineering:** Python · SQL · PostgreSQL · ETL/ELT · Pandas · Apache Airflow · Data Modeling (Star Schema) · Data Quality
- **Data Analysis:** SQL · Pandas · Excel · Pivot tables
- **Backend & APIs:** REST APIs · Django · Django REST Framework · JWT · Swagger · ASP.NET Core
- **Infrastructure & Tools:** Docker · Docker Compose · Git · GitHub Actions · CI/CD · Linux

---

### 🌐 Portfolio

- 💻 [**luizsoc.vercel.app**](https://luizsoc.vercel.app/)  
My portfolio with Data Engineering projects, skills and professional experience.
