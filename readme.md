
# HEDDA.IO

<img src="https://hedda.io/wp-content/uploads/2018/09/Hedda.io_primarylogo_orange-300x205.png" align="left" width="150"> oh22’s HEDDA.IO is a knowledge-driven data quality product completely built in Microsoft Azure. HEDDA.IO enables you to build a knowledge base and use it to perform a variety of critical data quality tasks, including correction, enrichment and standardization of your data. HEDDA.IO enables you to perform data cleansing by using cloud-based reference data services provided by reference data providers or developed and provided by yourself.


## Web App & SQL Deployment Template

With this Azure Resource Manager Template you can publish HEDDA.IO directly from the Azure Portal into an existing or a new resource group. The Azure Resource Manager (ARM) template creates all resources necessary for the operation of HEDDA.IO. This includes App service plan, App service, Azure SQL Server, Azure SQL Database. The application is preconfigured by the ARM template, further changes and configurations can be done later via the Azure Portal.

During the installation an API key is generated which you have to use to access HEDDA.IO. You can look at the API Key in the Application Settings of the App Service in the Applicaton Settings area and change it here if you wish.

After successful deployment, you must initialize HEDDA.IO once.

Open the URL 

##### https://<YOUR_APP_NAME>.azurewebsites.net 

and follow the instructions.

<a href="https://portal.azure.com/#create/Microsoft.Template/uri/https%3A%2F%2Fraw.githubusercontent.com%2Foh22is%2FHEDDA.IO%2Fmaster%2FApplication%2Fazuredeploy.json" target="_blank">
    <img src="http://azuredeploy.net/deploybutton.png" /> 
</a>



## Azure Data Factory SSIS-IR Deployment Template

The Azure Resource Manager (ARM) Template for Azure Datafctory SSIS-IR provides an own resource group together with an Azure SQL Server and an Azure Data Factory. For the Azure Data Factory an SSIS Integration Runtime and the corresponding SSISDB will be created.

The HEDDA.IO SSIS Data Cleansing component is pre-installed directly on the SSIS-IR nodes. So you can deploy your SSIS packages directly against the SSIS-IR and standardize, clean and enrich your data in the cloud.

<a href="https://portal.azure.com/#create/Microsoft.Template/uri/https%3A%2F%2Fraw.githubusercontent.com%2Foh22is%2FHEDDA.IO%2Fmaster%2FSSIS-IR%2Fazuredeploy.json" target="_blank">
    <img src="http://azuredeploy.net/deploybutton.png" /> 
</a>
