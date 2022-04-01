# Topic of the Template

SQL Server migration to Azure SQL Managed instance using Log replay lab tutorial. This template allows you to create a SQL Server instance on Virtual Machine which acts as a source for migration and a Azure SQL Managed instance inside a new virtual network. Storage account is already provisioned which is required to copy and transfer SQL Server backups between source and target.


# Topic Landing Zone

Description of the Landing zone

Solution overview and deployed resources. This deployment will create an In this tutorial, you migrate the AdventureWorks database from a self-hosted SQL Server instance to a SQL Server on Azure Virtual Machine with minimal downtime by using log replay service.



## Target audience

Example:
- Infrastructure Architect
- Application Developer
-       IT Professional
-       Cloud Solution Architect

# Product/LZ architecture

The [Template.json](https://github.com/Ganapathivarma07/LRS-Migration-AzureSQLMI/blob/master/template.json) Azure Resource Manager template will help you automatically deploy the diagram below, which includes:

example!!!

- A Virutal Network Gateway and a Public IP address.
- A Network Security Group with the necessary outbound rules for Azure Virtual Desktop Hostpools to properly activate and work.



[Template.json](https://github.com/Ganapathivarma07/LRS-Migration-AzureSQLMI/blob/master/template.json) can be modified to match your current infrastructure needs.

## One Click Deploying Teamplate
<!-- Powershell command for Translating Git URL for template.json
    $url = "https://raw.githubusercontent.com/Ganapathivarma07/LRS-Migration-AzureSQLMI/master/template.json?token=GHSAT0AAAAAABTCLTR2TGKXPWTERQWXINHSYSHBGIQ"
    [uri]::EscapeDataString($url)
    >> uri = https%3A%2F%2Fgithub.com%2FGanapathivarma07%2FLRS-Migration-AzureSQLMI%2Fblob%2F
master%2Ftemplate.json

Base URL: https://portal.azure.com/#create/Microsoft.Template/uri
Final URL: <Base URL>/<uri>
-->
[![Deploy to Azure](https://aka.ms/deploytoazurebutton)](https://portal.azure.com/#create/Microsoft.Template/uri/https%3A%2F%2Fraw.githubusercontent.com%2FGanapathivarma07%2FLRS-Migration-AzureSQLMI%2Fmaster%2Ftemplate.json%3Ftoken%3DGHSAT0AAAAAABTCLTR2TGKXPWTERQWXINHSYSHBGIQ)


## Deploying an ARM Template using the Azure portal

- Visit https://portal.azure.com



- Allow 30 minutes for the deployment to complete
- Peer your Hub and Spoke Virtual Networks as needed

## Azure services and related products

example!!
- Azure Networking
- Security

## Related references


1.	https://docs.microsoft.com/en-gb/azure/azure-sql/managed-instance/log-replay-service-migrate
2.	https://docs.microsoft.com/en-us/sql/relational-databases/backup-restore/backup-overview-sql-server?view=sql-server-ver15
3.	https://docs.microsoft.com/en-us/azure/storage/blobs/quickstart-storage-explorer
4.	https://docs.microsoft.com/en-us/azure/storage/common/storage-use-azcopy-v10
5.	https://techcommunity.microsoft.com/t5/azure-sql-blog/migrate-databases-from-sql-server-to-sql-managed-instance-using/ba-p/2144303


## License & Contribute

You are responsible for the performance, the necessary testing, and if needed any regulatory clearance for any of the models produced by this toolbox.
Please refer [LICENSE](LICENSE) &  [Contribute](https://github.com/git-pranayshah/AnalysisService/blob/master/Contribute.md) for more details


