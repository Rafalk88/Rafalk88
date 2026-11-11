<h1 align="center">Hi, I'm Rafał 👋</h1>
<h3 align="center">I turn healthcare finance data into Power BI reports 📊🏥</h3>

<p align="center">
  <a href="https://www.linkedin.com/in/rafalkochanecki"><img src="https://img.shields.io/badge/LinkedIn-Let's%20connect-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn"></a>
  <img src="https://img.shields.io/badge/PL--300-in%20progress-F2C811?style=for-the-badge" alt="PL-300 in progress">
  <img src="https://img.shields.io/badge/Based%20in-Poland-DC143C?style=for-the-badge" alt="Poland">
</p>

---

### 🙋‍♂️ About me

- 🏥 I work in the finance department of a rehabilitation clinic: procedure billing and **NFZ contract** fulfilment
- 📊 I'm building **Power BI** reports on top of my own **SQL data warehouse**
- 🛠️ On the side I write the app that will feed that warehouse (NestJS + PostgreSQL)
- 💬 Ask me about: contract points, no-show rates, star schemas, or why a visit with an X-ray takes 45 minutes

### 🧰 Tech I use

<p>
  <img src="https://img.shields.io/badge/Power%20BI-F2C811?style=flat-square" alt="Power BI">
  <img src="https://img.shields.io/badge/DAX-F2C811?style=flat-square" alt="DAX">
  <img src="https://img.shields.io/badge/Power%20Query-F2C811?style=flat-square" alt="Power Query">
</p>

<a href="https://skillicons.dev"><img src="https://skillicons.dev/icons?i=postgres,py,docker,ts,nestjs,nextjs,react,git" alt="Skills"></a>

### 🚀 Projects

| | Project | In one line |
|:-:|---|---|
| 📊 | [**rehab-contract-dashboard**](https://github.com/Rafalk88/rehab-contract-dashboard) | Power BI: contract fulfilment, clinic workload, no-shows. Star schema in PostgreSQL, synthetic data. 🚧 Dec 2026 |
| 📘 | [**rehab-module**](https://github.com/Rafalk88/rehab-module) | Main docs of a web app for rehab clinics: modules, roles, security |
| ⚙️ | [**rehab-backend**](https://github.com/Rafalk88/rehab-backend) | NestJS, PostgreSQL + Prisma, encrypted medical data, audit log |
| 🖥️ | [**rehab-frontend**](https://github.com/Rafalk88/rehab-frontend) | Next.js, React, Ant Design |

### 🔗 How it fits together

```mermaid
flowchart LR
    A["⚙️ rehab app<br/>NestJS + PostgreSQL"] --> W[("🗄️ SQL warehouse<br/>star schema")]
    B["📄 NFZ procedure<br/>catalogue"] --> W
    C["📄 Contract plan"] --> W
    W --> P["📊 Power BI"]
```

### 🌱 Right now

- 🔨 Building the warehouse and report 1 for `rehab-contract-dashboard`
- 📚 Studying for **PL-300** (Microsoft Power BI Data Analyst)

<p align="center"><i>Thanks for stopping by! 🙌</i></p>
