## **Getting Started**

1. Once the environment is provisioned, a virtual machine and lab guide will get loaded into your browser. Use this virtual machine throughout the workshop to perform the lab.
   
   ![LabEnvironment](images/vmandguide-env2.png)
   
1. To get the lab environment details, you can select the Environment Details tab. Additionally, the credentials will also be sent to your email address provided during registration.

   ![LabEnvironment](images/envdetails-env2.png)

1. Note the **Suffix** value from the Environment Details tab in a notepad and please use it in the lab steps wherever required.

1. You can also open the Lab Guide on a separate full window by selecting the **Split Window** button on the bottom right corner.

   ![LabEnvironment](images/split-window.png)

### Log-in to the Azure portal and verify the pre-deployed resources

1. In the LabVM, double click on the **Azure portal** shortcut on the desktop.

     ![LabEnvironment](images/azureshortcut.png) 
     
1. On **Sign in to Microsoft Azure** blade, you will see a login screen, in that enter the following email/username and then click on **Next**.  
   * **Azure Username/Email**:  <inject key="AzureAdUserEmail"></inject>
   * **Azure Password**:  <inject key="AzureAdUserPassword"></inject>
  
1. If you see the pop-up like below, click **Skip for now(14 days until this is required)**.

   ![LabEnvironmentpop-up](images/skip.png)

1. If you see the pop-up  **Stay Signed in?**, click **No**.

1. If you see the pop-up **You have free Azure Advisor recommendations!** , close the window to continue the lab. 

1. If a **Welcome to Microsoft Azure** popup window appears, click **Maybe Later** to skip the tour.

1. Now you can see the Azure Portal Dashboard, click on **Resource groups** from the Navigate panel to see the resource groups.
   
   ![lab1 rg](images/rg.png "resource group") 
     
1. Navigate to the **data-engineering-synapse-02** Resource group and verify whether you have all the below resources deployed successfully.
  
    ![lab1 rg](images/env02-rg.png "env2 resource group") 

   - Storage account
   - Synapse workspace
   - Apache Spark pool
 
 1. Click on **Next** from the bottom right corner and follow the instructions to perform the lab.

### Modules Included

   In this hands on lab you will perform the following module:

 - **Module 2 - Run interactive queries using serverless SQL pools** 

