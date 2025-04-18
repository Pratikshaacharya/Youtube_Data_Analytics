# Youtube_Data_Analytics <br><br>

<b>Overview</b>
<br><br>
This project is designed to build a scalable, cloud-based data engineering pipeline that ingests, processes, stores, and analyzes YouTube video data. It focuses on both structured and semi-structured datasets, particularly around video categories and trending metrics. The ultimate goal is to uncover valuable insights through interactive dashboards and visual reporting tools.
<br><br>
<b>Project Objectives</b><br>
1. **Data Ingestion** : Design and implement a reliable mechanism to ingest data from various sources.<br>
2. **ETL (Extract, Transform, Load)** : Transform raw data into a structured and clean format ready for analysis.<br>
3. **Data Lake**: Use a centralized storage repository to consolidate data from different sources for ease of access and analysis.<br>
4. **Scalability** : Ensure the system architecture is capable of scaling as data volume and complexity grow.<br>
5. **Cloud Infrastructure** : Leverage AWS cloud services to manage, process, and store data efficiently, enabling serverless, secure, and highly available systems.<br>
6. **Reporting & Visualization** : Build insightful, interactive dashboards to answer key business and analytical questions.<br>

<br><br>
<b>Technologies & AWS Services Used</b><br><br>
<b>Amazon S3</b> : Acts as the central data lake, storing both raw and processed data securely and durably.<br>
<b>AWS IAM (Identity and Access Management)</b> : Controls user access and permissions to AWS resources, ensuring secure operations.<br>
<b>AWS Glue</b> : A serverless data integration service used to discover, catalog, and transform data for analytics and machine learning.<br>
<b>AWS Lambda</b> : Runs backend processing logic without the need to provision or manage servers.<br>
<b>Amazon Athena</b> : Enables SQL-based querying directly on data stored in S3—no need for data loading or traditional databases.<br>
<b>Amazon QuickSight</b> : A serverless business intelligence tool used to build visual dashboards for data-driven decision-making.<br>
