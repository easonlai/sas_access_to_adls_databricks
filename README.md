# Using SAS to authenticate and access to ADLS Gen 2 from Azure Databricks

This is code sample of how to use [Shared Access Signatures (SAS)](https://docs.microsoft.com/en-us/azure/storage/common/storage-sas-overview) to authenticate and access to [ADLS Gen 2](https://docs.microsoft.com/en-us/azure/storage/blobs/data-lake-storage-introduction) from [Azure Databricks](https://docs.microsoft.com/en-us/azure/databricks/scenarios/what-is-azure-databricks). You can generate SAS from Container, Folder, Sub-Folder, File level for specific access permission (e.g. read, list, write, etc...). Then using Databricks to access ADLS particular Container, Folder, Sub-Folder or individual file with specific SAS key.

Enjoy.

