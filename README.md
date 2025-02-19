# ADLS-Azure-Databricks

Project idea: 
(Spark)

Push data from the Azure Data Lake(ADLS Gen2) into Spark through Databricks.


So first get data from Data World which has about 130 000 free data sets
and then dump them into an ADLS Gen2 container, this is the most modern types
of storage units in this year.

Next load the files into Databricks. You're going to need to set up a Databricks cluster
and then mount the ADLS Gen2 container into Databrick's File System (DBFS),then after that
read the data into a Spark data frame 

1. Create ADLS Gen2 container(allows  big data services like Azure Databricks ton apply data processing frameworks such as Apache Spark)
2. Create Azure Databricks workspace-(specify pricing tier)
3. After you provision Azure Databricks workspace, you can use Azure Databricks portal to work with data and compute resources.
