# Olympics Data Analytics
Olympics Data Analytics End-to-End Azure Data Engineering Project

**Resources and Technologies Used**
- Azure - Azure Factory, Azure Databricks, Azure Data Lake 2, Azure Synapse Analytics
- Kaggle dataset - (https://www.kaggle.com/datasets/arjunprasadsarkhel/2021-olympics-in-tokyo)

**Architecture of project**
- Took data from Kaggle in xlxs format and converted to csv.
- Added data(raw-data) to github.
- Created a new Data Factory in Azure and uploaded data using Git Hub.
- From the data factory, connected Data Lake Gen 2 and added all files.
- Used Databricks to transformation of data.
- Added transformed data to Data Lake again.

**Some basic knowledge about _Azure tools_**
- Why Azure Data Factory
  Azure Data Factory is a cloud-based data integration service provided by Microsoft Azure. It allows you to create, schedule, and manage data pipelines
  for ETL (Extract, Transform, Load) processes, enabling you to efficiently move and transform data from various sources to different destinations.
  _Data movement_: Transfer data between different data stores.
  _Transformation_: Perform data transformations using services like Azure HDInsight, Azure Data Lake Analytics, etc.
  _Orchestration_: Chain activities into end-to-end workflows.
  _Integration_: Seamlessly integrate with other Azure services.
  _Monitoring and management_: Monitor pipeline execution and troubleshoot issues.

- 


