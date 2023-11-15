<p align="center">
 <img src="https://github.com/Velezdrv/Azure-Portal-Tutorial/assets/147437260/0c92122c-77df-44df-bc1a-6c4f6a0bc33a&auto=format&fit=crop&w=2772&q=80" width="200" height="200" border="10"/>
</p>
   
<h1 align="center">Azure-Portal-Tutorial</h1>

<h2>Environments and Technologies Used</h2>

- Microsoft Azure
- Windows 11 Pro

<h2>Microsoft Azure Website</h2>

- https://portal.azure.com/?quickstart=true#home

- Upon logging into Azure Portal, the first page you should see is always the Home Page
  - The Home Page offers multiple ways to access the Azure Portal's resources, one being the Search Bar at the top center and notable headings
  - Azure Services - The Services in Azure Portal that updates with most recent Resources used; all of Azure Portal's Services can be located on a seperate page by going to More Services
  - Resources - A listing that displays and updates whenever Resources (Resource Groups, Virtual Machines, Network Security Groups, etc.) are created or recently modified
  - Navigate - A quality of life heading allowing users to easily navigate to the essentials of their account, notably Resources and Subscriptions
  - Tools - Heading that offers quick links to the infastructure and cost of the resources used in Azure as well as the online course Microsoft Learn for further education how to use Microsoft Azure

![image](https://github.com/Velezdrv/Azure-Portal-Tutorial/assets/147437260/030f734f-15a0-4194-94ab-ce9a4416bd62)

<h2>Creating a Resource Group</h2>

- Resource Groups serves as the base for many of Microsoft Azure's services and tools. To use Virtual Machines or Network Security Groups, you need a Resource Group.
Head to the Resource groups page and click on create

![image](https://github.com/Velezdrv/Azure-Portal-Tutorial/assets/147437260/ea56809f-bcbb-452a-84ef-38f2ff80c0b8)

- Resource Groups have 3 fields for creation
  - Basics - Tab where you enter the name of your Resource Group and Subscription it is linked to for billing upon the use of Resources in that Group
  - Tags - Simple organizational tool for managing resources and view consolidated billing by applying the same tag to multiple resources and resource groups
  - Review + Create - Validation processing to check if credentials (notably a name) are filled and the Subscription is usable
- After validation passed, click on Create in the bottom and your Resource Group is created. Note: based on server speed and Internet connection, Resources and Resource Groups will take some time to deploy, take note of the notification bell at the top right to see when deployment is complete

![image](https://github.com/Velezdrv/Azure-Portal-Tutorial/assets/147437260/f0565785-5b81-4ab3-bbca-97b78d9fdcd8)

<h2>Clean UP</h2>

 - When done using your newly created Resource Group, if you no longer need it, Delete it, as you will continue to be charge for it periodically.
   - Head to the Resource Group and select Delete to open a window on the right. Deletion of the Resource Group require verification by entering its name, it's also convenient since it deletes all resources in that group
  
  ![image](https://github.com/Velezdrv/Azure-Portal-Tutorial/assets/147437260/a6ecf8c3-3e7d-4e04-bb42-654e08eae85e)
