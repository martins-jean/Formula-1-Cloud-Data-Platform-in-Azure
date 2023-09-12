# Formula 1 Cloud Data Platform in Azure

Data engineering project using Data Lake Gen2, Data Factory, Databricks (PySpark, Spark SQL) and Power BI.

## Architecture Diagram

![Screenshot 2023-09-12 at 09 04 15](https://github.com/martins-jean/Formula-1-Cloud-Data-Platform-in-Azure/assets/118685801/967fc952-6c20-4d24-9991-ca76a781096d)

## Project Overview

## Reproducibility Guidelines

<details>
  <summary>
    Required setup
  </summary>
  1. Create a premium tier Azure Databricks service in the Azure portal. If you want the workspace to be created within your own Vnet, you can specify that under the networking configurations. If you want double encryption, the premium tier allows you to enable infrastructure encryption under the advanced tab. You can then add any tags for later identification and billing purposes. Microsoft is now limiting the cluster nodes available for free and student subscriptions so I created my workspace in the UK South region and within Databricks, I used a Standard_D4a_v4 Single Node cluster. Review and create the resource, it should take around five minutes for the deployment to be complete. <br>
  2. Navigate to the resource page, pin the service to a new dashboard so you can easily access all the resources linked to this project later. You can view your newly created dashboard by clicking on the top left menu, dashboard and then on the drop down menu to view the different Azure dashboards you have. You can also share this dashboard with your team so everyone can access the required resources related to a specific project. Once that's done, go ahead and launch your Databricks workspace.
</details>

<details>
  <summary>
    Workspace configuration
  </summary>
  1. Under workspace, add the repository you created on your version control platform to sync it with Databricks. <br>
  2. Click the compute icon and start creating an all-purpose cluster. Change the name of the cluster at the top. Leave the policy as unrestricted so you can manually configure your cluster according to your needs. 
</details>

<details>
  <summary>
    
  </summary>
</details>

<details>
  <summary>
    
  </summary>
</details>

<details>
  <summary>
    
  </summary>
</details>
