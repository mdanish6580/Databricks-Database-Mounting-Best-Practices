# Databricks Configuration with Data Sources in Azure Managed Environment
## Important things to remember
* **Key Vaut:** It's just a safe case managed by Azure and here we keep all our secret credentials in order to avoid unauthorized access.
* **Mount:** It's a technical terminology used to connect your computation environment with that of datastore.
## **This Key Vault is the only difference between best practices and usual practices. Meaning, if we are able to avoid unauthorised access then it is a best practice else not.**


## Multiple Sources are possible for such configuration
* Azure blob storage
* Azure Data lake gen 2 (recommended)
* Azure Data lake gen 1 (Probably depricated and not recommended)
* Azure SQL Database
