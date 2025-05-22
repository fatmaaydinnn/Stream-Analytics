📌 Lab: Building Real-Time Pipelines in Cloud Data Fusion

🔍 Objective
To learn how to build real-time data processing pipelines on Google Cloud using Cloud Data Fusion. The goal was to ingest, transform, and load streaming data into BigQuery for real-time analysis.

⚙️ Technologies and Services Used
Google Cloud Data Fusion
Used to visually design and deploy data pipelines.

Google Cloud Pub/Sub
Provided real-time data streaming capabilities.

Google BigQuery
Served as the destination for processed data and analysis.

Cloud Shell & GCP Console

📈 Implementation Steps
Creating a Data Fusion Instance

Launched the Cloud Data Fusion service.

Chose the Standard edition.

Setting Up a Pub/Sub Topic

Created a topic to simulate real-time data publishing.

Sample messages were published manually.

Designing the Data Pipeline

Built the pipeline in the Cloud Data Fusion UI.

Configured Pub/Sub as the source.

Added a transformation step (e.g., using Wrangler).

Defined BigQuery as the sink (destination).

Deploying and Running the Pipeline

Deployed the pipeline to begin processing streaming data.

Viewing Results in BigQuery

Verified that data was successfully loaded into BigQuery.

Queried the table using SQL for analysis.

🧠 Key Learnings
How to build pipelines without writing code using visual tools

Real-time data ingestion with Pub/Sub

Data transformation and routing in Cloud Data Fusion

BigQuery integration for scalable data analytics

✅ Outcome
This lab provided hands-on experience in building end-to-end real-time data pipelines on GCP. It reinforced key concepts in data engineering and real-time data processing.
