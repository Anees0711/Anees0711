<h1 align="center">Anees Ahmad Abbasi</h1>

<p align="center">
  <b>Data Engineer · ML Engineer</b><br>
  Paris, France
</p>

<p align="center">
  <a href="mailto:abbasi-anees.ahmad@outlook.com"><img src="https://img.shields.io/badge/Email-abbasi--anees.ahmad@outlook.com-0A66C2?style=for-the-badge&logo=microsoftoutlook&logoColor=white" alt="Email"></a>
  <a href="https://www.linkedin.com/in/anees-abbasi-30109b1b0/"><img src="https://img.shields.io/badge/LinkedIn-Connect-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn"></a>
  <img src="https://img.shields.io/badge/Open_to-Data_·_ML_·_MLOps_roles-2EA44F?style=for-the-badge" alt="Open to work">
</p>

---

## Hey, I am Anees

I build data and ML systems that survive contact with production.

Notebooks are easy. What is hard is the version of the same problem where the sensor drops offline for six hours, the schema changes without warning, and someone in operations needs an answer before the next shift starts. That is the part of the job I actually enjoy.

I have spent the last few years moving between telecom analytics in Pakistan, data and AI work in Dubai, and industrial IoT machine learning in Paris. Different industries, same underlying fight: turn messy real world data into something a business can trust and act on.

Right now I am finishing an **MSc in Data Engineering and AI at DSTI** while working in alternance, and I am **open to Data Engineer, ML Engineer, MLOps and DevOps roles.**

---

## How I work

**I start from the failure mode, not the model.**
Before I build anything I ask what breaks it. Late data, drifting sensors, silent schema changes, a model that quietly degrades for three months. Most production incidents are not exotic. They are things nobody bothered to check.

**I do not hand over things people cannot use.**
A model behind an endpoint with docs beats a better model in a notebook. Every project I ship has a way for a non data person to actually query it.

**I automate anything I have done twice.**
Docker, Terraform, GitHub Actions, Azure DevOps. Manual deployment steps are just future incidents with a delay.

**I optimise for the number that matters, not the one that looks good.**
On IoT anomaly detection, precision beat recall every time. An alerting system that cries wolf gets ignored within a week, and then it may as well not exist.

---

## Tech I use in practice

| Area | Tools |
|---|---|
| **Data Engineering** | PySpark · Databricks · Delta Lake · Snowflake · Kafka · Airflow · Azure Data Factory |
| **Cloud** | Azure (ADLS, Event Hub, Functions, Azure ML, Synapse) · AWS |
| **ML & Deep Learning** | PyTorch · TensorFlow / Keras · Scikit-learn · XGBoost · LSTM · YOLO |
| **Computer Vision** | OpenCV · CNN · DETR · Transfer Learning |
| **MLOps & Infrastructure** | MLflow · Docker · Kubernetes · Terraform · GitHub Actions · Azure DevOps |
| **Storage & Serving** | SQL · InfluxDB · MongoDB · Azure Blob · FastAPI · Streamlit · Power BI |

---

## Things I have built

### Real-Time Data Lakehouse with Streaming ML
Most teams run streaming and ML as two disconnected systems, then spend months gluing them together. This one does not. Structured Streaming lands into Delta tables through medallion layers, and model scoring sits inside the same flow instead of bolted on afterwards.

`Spark Structured Streaming` `Delta Lake` `Databricks` `Kafka`
**→** [View repository](https://github.com/Anees0711/Real-Time-Data-Lakehouse-Streaming-ML-Platform.git)

---

### Real-Time Churn Prediction on Azure
A nightly churn batch job tells you about churn after it already happened. This pipeline scores risk as the customer event arrives. Event Hub feeds Azure Functions, which call a deployed ML endpoint, write scores to SQL, and surface them in Power BI. Retention teams see risk while they can still do something about it.

`Azure Event Hub` `Azure Functions` `Azure ML` `SQL` `Power BI`
**→** [View repository](https://github.com/Anees0711/Azure-realtime-churn-prediction.git)

---

### Turbofan Engine Failure Prediction with LSTM
Predictive maintenance on the NASA C-MAPSS dataset, framed as a sequence problem: read multi sensor history, predict remaining cycles before failure. **R² = 0.87.** More importantly, I shipped it as a FastAPI service with a Streamlit interface, so a maintenance engineer can query it directly instead of waiting on a data scientist to rerun a notebook.

`PyTorch` `LSTM` `FastAPI` `Streamlit` `Docker`
**→** [View repository](https://github.com/Anees0711/LSTM_Model.git)

---

### End-to-End Retail Data Pipeline on Databricks
The Bronze, Silver and Gold pattern done properly. Raw ingestion, cleaning and conformance, business level aggregates, then a Power BI semantic layer analysts can query without asking me what a column means.

`PySpark` `Delta Lake` `Databricks` `Power BI`
**→** [View repository](https://github.com/Anees0711/End-to-End-Retail-Data-Pipeline-on-Databricks.git)

---

### Snowflake and Azure ADLS Data Pipeline
The lake to warehouse pattern most enterprises actually run. Staged loading from Azure Data Lake Storage into Snowflake, with modelled analytics tables at the end rather than a raw dump nobody can query.

`Snowflake` `Azure ADLS` `SQL` `Python`
**→** [View repository](https://github.com/Anees0711/Snowflake-and-Azure-ADLS-Data-Pipeline.git)

---

### IoT Anomaly Detection Pipeline · Artifeel
Real time telemetry from industrial IoT devices, anomaly detection deployed on Azure ML. The model was the easy part. The real problem was irregular signals and slow temporal degradation, the kind of pattern where a naive threshold either fires constantly or never fires at all. Getting that balance right was the entire job.

`Python` `Scikit-learn` `Azure ML` `InfluxDB`

---

## Also worth a look

| Project | What is inside |
|---|---|
| [House Price Predictive Model Pipelines](https://github.com/Anees0711/House-price-predictive-model-pipelines.git) | Regression modelling wrapped in reproducible Scikit-learn pipelines, with feature engineering and honest evaluation |
| [End-to-End Data Engineering Project](https://github.com/Anees0711/end-to-end-data-engineering-project-4413618.git) | A full ingestion to serving workflow, built as a reference implementation |
| [OpsTeamFlow AI](https://github.com/Anees0711/Opsteamflow-ai.git) | AI assisted operations workflow tooling |

---

## Certifications

**Databricks** · Certified Data Engineer Professional

**Microsoft** · DP-700 · DP-600 · DP-100 · AZ-400 · AZ-104 · PL-900

**Databricks Academy** · Lakeflow Jobs · Lakeflow Connect · Spark Declarative Pipelines · DevOps for Data Engineering

---

## Where I have been

**Artifeel**, Paris · Data and ML Engineer — IoT anomaly detection and Azure ML deployment

**Evamp & Saanga**, Islamabad · Data Analytics Engineer

**Lune**, Dubai · Data and AI Engineer

**PTCL**, Pakistan · Data Analyst

3 countries, three very different definitions of what counts as clean data. Telecom taught me scale. Consulting taught me to ship on a deadline. IoT taught me that the tutorial dataset lied to all of us.

---

## Let us talk

I am currently open to:

- Full time **Data / AI / ML Engineering** roles in France or remote
- Freelance data platform and ML delivery work
- Computer vision and IoT analytics consulting

<p align="left">
  <a href="mailto:abbasi-anees.ahmad@outlook.com"><img src="https://img.shields.io/badge/Email_me-abbasi--anees.ahmad@outlook.com-0A66C2?style=flat-square&logo=microsoftoutlook&logoColor=white" alt="Email"></a>
  <a href="https://www.linkedin.com/in/anees-abbasi-30109b1b0/"><img src="https://img.shields.io/badge/LinkedIn-anees--abbasi-0A66C2?style=flat-square&logo=linkedin&logoColor=white" alt="LinkedIn"></a>
</p>
