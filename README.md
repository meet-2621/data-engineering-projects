
Data Engineering Projects
A collection of hands-on Data Engineering projects exploring data modeling, ETL pipelines, cloud data platforms, and workflow orchestration using Python, SQL, Apache Spark, Apache Airflow, PostgreSQL, Apache Cassandra, and AWS.

Project note: This repository is based on a collection of Udacity Data Engineering learning projects. Review the original source and license, and add appropriate attribution before publishing. Update this README to reflect any changes you personally make.

Projects Included
1. Data Modeling with PostgreSQL
Build a relational database and ETL pipeline for a music streaming use case. The project organizes song and user activity data into tables for analysis.

Key technologies: Python, PostgreSQL, SQL, ETL

2. Data Modeling with Apache Cassandra
Model music-app activity data in Cassandra, designing tables around specific query requirements.

Key technologies: Python, Apache Cassandra, NoSQL

3. Data Warehouse on AWS
Load song metadata and user activity logs from Amazon S3 into an Amazon Redshift data warehouse for analytical queries.

Key technologies: Python, SQL, Amazon S3, Amazon Redshift, ETL

4. Data Lake with Apache Spark
Read JSON song and event data from S3, transform it with Spark, and write analytics-ready data back to S3 in columnar Parquet format.

Key technologies: Python, Apache Spark, AWS S3, Amazon EMR, Parquet

5. Data Pipelines with Apache Airflow
Orchestrate ETL workflows with Airflow DAGs and custom operators for staging data, loading fact and dimension tables, and running data-quality checks.

Key technologies: Python, Apache Airflow, Amazon Redshift, SQL

6. API Data to PostgreSQL
Fetch business data from an API and load the results into a PostgreSQL database for querying and analysis.

Key technologies: Python, REST API, PostgreSQL, ETL

7. AWS Infrastructure and Services
Supporting scripts and documentation for AWS services and infrastructure setup, including Redshift and Airflow-related resources.

Key technologies: AWS, CloudFormation, Python

Technology Stack
Programming: Python
Databases: PostgreSQL, Apache Cassandra, Amazon Redshift
Data processing: Apache Spark, PySpark
Workflow orchestration: Apache Airflow
Cloud: Amazon Web Services (AWS), including S3, EMR, and Redshift
Data formats: JSON, Parquet
Concepts: ETL/ELT, data modeling, data lakes, data warehousing, data pipelines, data quality
Repository Structure
.
├── AWS_Services/
├── Airflow_Data_Pipelines/
├── Data_Api_to_Postgres/
├── Data_Lake/
├── Data_Modeling_with_Apache_Cassandra/
├── Data_Modeling_with_Postgres/
├── Data_Warehouse/
├── Airflow_CloudFormation.yaml
├── Redshift_Cluster_IaC.py
└── README.md
The repository may also contain supporting configuration files, setup notes, and project assets.

Getting Started
Clone the repository:

git clone https://github.com/YOUR-USERNAME/data-engineering-projects.git
cd data-engineering-projects
Choose a project folder and read its README or setup instructions.

Install the dependencies required by that individual project.

Configure your local database or AWS resources as described in the project documentation.

Run the scripts or workflows using the instructions provided for that project.

Requirements differ by project, so there is no single command that runs the entire repository.

Security Notes
Never commit AWS access keys, database passwords, API tokens, private keys, or other secrets.
Keep credentials in environment variables or a local configuration file excluded through .gitignore.
Use placeholders in example configuration files.
Review all files before pushing to GitHub, especially configuration files and notebooks.
Learning Outcomes
These projects provide practice with:

Building ETL and ELT pipelines
Designing relational and NoSQL data models
Processing large datasets with Spark
Building cloud-based data lakes and warehouses
Orchestrating scheduled workflows with Airflow
Integrating API data with databases
Understanding data quality and cloud infrastructure
Attribution
This repository is intended for learning and practice. If you are using or adapting an existing project collection, preserve its original license and attribution requirements. Add your own implementation details, improvements, and learnings so visitors can distinguish your contributions from the original work.
