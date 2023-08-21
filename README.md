![Project Architecture](https://github.com/rishkhandelwal/OlampicsData-DataEngineering/blob/main/archiOlym.png)
# Olympics Data Analytics
Olympics Data Analytics End-to-End Azure Data Engineering Project

## Resources and Technologies Used
- Azure - Azure Factory, Azure Databricks, Azure Data Lake 2, Azure Synapse Analytics, SQL
- Kaggle dataset - (https://www.kaggle.com/datasets/arjunprasadsarkhel/2021-olympics-in-tokyo)

**Architecture of project**
1. Took data from Kaggle in xlxs format and converted it to csv.
2. Added data(raw-data) to github.
3. Created a new Data Factory in Azure and uploaded data using Git Hub.
4. From the data factory, connected Data Lake Gen 2 and added all files.
5. Used Databricks for the transformation of data.
6. Added transformed data to Data Lake again.
7. Used Azure Synapse Analytics to analyze data using graphs.

**Some basic knowledge about _Azure tools_**
- Why Azure Data Factory?
  Azure Data Factory is a cloud-based data integration service provided by Microsoft Azure. It allows you to create, schedule, and manage data pipelines
  for ETL (Extract, Transform, Load) processes, enabling you to efficiently move and transform data from various sources to different destinations.
  - Use Cases:
    - _ETL (Extract, Transform, Load) processes_: Moving and transforming data from source to destination.
    - _Data integration_: Integrating data from diverse sources for analytics, reporting, and business intelligence.
    - Orchestration_: Creating complex workflows to manage data processing and transformations.
  - Key Features:
    - _Data movement_: Transfer data between different data stores.
    - _Transformation_: Perform data transformations using services like Azure HDInsight, Azure Data Lake Analytics, etc.
    - _Orchestration_: Chain activities into end-to-end workflows.
    - _Integration_: Seamlessly integrates with other Azure services.
    - _Monitoring and management_: Monitor pipeline execution and troubleshoot issues.

- Why Azure Data Lake?
  Azure Data Lake is a scalable and secure cloud-based data lake storage service that allows you to store and analyze large volumes of structured and
  unstructured data at any scale.
  - Use Cases:
    - _Big data analytics_: Storing and analyzing massive amounts of data for insights and analytics.
    - _Data archiving_: Long-term storage of historical or infrequently accessed data.
    - _Machine learning and AI_: Storing and processing data for training machine learning models.
  - Key Features:
    - _Scalability_: Store massive amounts of data without worrying about infrastructure.
    - _Data flexibility_: Supports structured and unstructured data formats.
    - _Advanced analytics_: Integrate with tools like Azure Databricks for data processing and analytics.
    - _Security and access control_: Implement fine-grained access control to protect data.
 
**Description of files**
- data - this contains raw data cvs file
- transformed-data - this contains data that can be used used to build a dashboard.
- ipynb file - contains Pyspark transformation code

**Work for Future**
Can create dashboard using transformed data using tableau, PowerBI, etc.

