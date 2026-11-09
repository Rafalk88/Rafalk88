# Hi, I'm Rafał 👋

I work with healthcare finance data in an outpatient rehabilitation setting: procedure billing and NFZ contract fulfilment. I turn that domain knowledge into **Power BI reports built on my own SQL data warehouse**, and I write the backend that will feed it.

**Stack:** Power BI · DAX · Power Query · SQL · PostgreSQL · Python (pandas) · NestJS / TypeScript

## Projects

| Project | What it is |
|---|---|
| [rehab-contract-dashboard](https://github.com/Rafalk88/rehab-contract-dashboard) | Power BI report on NFZ contract fulfilment, clinic workload and no-shows. Star-schema warehouse in PostgreSQL (staging → dw), idempotent loads, data quality checks. Synthetic data. 🚧 Dec 2026 |
| [rehab-module](https://github.com/Rafalk88/rehab-module) | Backend for a rehabilitation unit: NestJS, PostgreSQL, encryption of medical data, role-based permissions, audit log. From January it becomes a data source for the warehouse above. |

## How it fits together

```
rehab-module (NestJS + PostgreSQL)  ─┐
NFZ procedure catalogue (file)      ─┼─→  PostgreSQL warehouse (star schema)  →  Power BI
Contract plan (file)                ─┘
```

## Now

- Building the SQL warehouse and report 1 for `rehab-contract-dashboard`
- Studying for **PL-300** (Microsoft Power BI Data Analyst)

📫 [LinkedIn](https://www.linkedin.com/in/rafalkochanecki)
