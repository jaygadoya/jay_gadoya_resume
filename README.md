<div align="center">
**Jay Gadoya**
</div>

**Data Engineer**

📞 +91 9075347449 &nbsp;|&nbsp; ✉️ [jaygadoya123@gmail.com](mailto:jaygadoya123@gmail.com) &nbsp;|&nbsp; 🔗 [LinkedIn](https://linkedin.com/in/jay-gadoya1) &nbsp;|&nbsp; 💻 [GitHub](https://github.com/jaygadoya)

---

## Summary

Data Engineer with 3+ years of experience building batch and streaming pipelines on healthcare data using Spark, Python, and SQL in a Databricks and AWS environment. Built a metadata-driven ingestion framework that loads ~80 GB/day of raw files across all pipelines, with automated business notifications and a reusable template adopted across teams. Experienced in medallion architecture, Redshift warehousing, and delivering pipelines end to end through to FastAPI-backed dashboards, orchestrated with Airflow and Stonebranch.

---

## Education

**Chandigarh University**, Chandigarh, India
Bachelor of Engineering – Aerospace Engineering | CGPA: 7.45
*Aug 2020 – June 2024*

---

## Experience

### Data Engineer — Perficient
*Gurgaon, India | May 2024 – Present*

- Built a metadata-driven ingestion framework that loads ~80 GB/day of raw files across multiple file formats, powering all production pipelines and enforcing consistent code quality. It is used by nearly all production users.
- Designed batch and streaming pipelines using Spark, Python, and SQL on Databricks (AWS) with the medallion architecture, applying healthcare business logic in SQL and loading curated data into Amazon Redshift. Orchestrated with Airflow and Stonebranch, optimized for low latency.
- Led the migration of healthcare datasets from on-premises Hadoop (HDFS) to Amazon S3, re-platforming legacy workloads onto Databricks on AWS with the medallion architecture, and validating data integrity through row-count reconciliation, checksum comparison, and schema checks between source and target.
- Integrated an automated email notification service using Python (`smtplib`, `email.mime`) that sends HTML-formatted alerts to business stakeholders after each data load, with load status, record counts, and failure details populated dynamically from pipeline metadata. Created a single parameterized HTML template (Jinja2) reused across teams.
- Delivered end-to-end pipelines through to dashboards, serving key metrics from PostgreSQL via FastAPI with Redis caching, using SQLAlchemy and Alembic, and supporting the dashboard's CRUD application.
- Ingested clickstream data using Kafka, processed it with Spark, and stored analytics-ready output in Redshift; also sourced MongoDB member data to build a pipeline for coverage trend analysis loaded into Redshift.

### Data Analyst Intern — B Cloud
*Gurgaon, India | Jan 2024 – May 2024*

- Analyzed and cleaned large datasets using Python (Pandas, NumPy) and SQL, writing queries with joins, aggregations, and window functions to extract insights that supported business decision-making.
- Built automated reports and visualizations (using Matplotlib/Seaborn or Power BI/Tableau) to track key metrics, reducing manual reporting effort and helping stakeholders quickly spot trends.

---

## Projects

### Meta-data Driven Type-2 Data Load Engine
`Python` `SQL` `Spark` &nbsp;|&nbsp; [GitHub: Meta-data Driven](https://github.com/jaygadoya)

- Built a config-driven PySpark pipeline that reads JSON configuration files to define data sources, SQL file paths, and output targets, so new datasets could be onboarded by editing config instead of changing code.
- Designed the pipeline to be modular and reusable, with parameterized inputs, logging, and error handling, making it easy to maintain, test, and extend across multiple jobs and environments.
- Loaded data from SQL sources into Spark DataFrames by dynamically reading query files from configured paths and executing them through Spark SQL/JDBC.

---

## Certificates & Achievements

- 🏅 Databricks Certified Data Engineer Associate
- 🏅 Databricks Certified Data Engineer Professional
- 🏆 **Extra Mile Award** — Awarded by BCBSMI for architecting the batch pipeline and resolving production pipeline bottlenecks.

---

## Technical Skills

| Category | Skills |
|---|---|
| **Programming Languages** | Python, SQL, NoSQL, JavaScript |
| **Databases** | MySQL, PostgreSQL, MongoDB, Redis, Redshift |
| **Cloud & Warehousing** | AWS, Redshift, Medallion Architecture |
| **Big Data & Streaming** | Spark, Databricks, Kafka |
| **Frameworks, Tools & Technologies** | Amazon Athena, FastAPI, Django, PyTest, SQLAlchemy, Git, Alembic, Docker, Jenkins, RESTful Web Services, Linux |
| **AI Tools** | GitHub Copilot, Claude (for boilerplate code generation) |
