**Image Classification on Places 365 Dataset**
------------------------------------------------
**About the Project**
------------------------------------------------
This project aims to classify images of places using a Convolutional Neural Network (CNN) leveraging Azure's cloud services for efficient data processing, training, and deployment. It utilises Places365 dataset obtained from the Kaggle dataset and uploaded to Azure Blob Storage for cloud processing. The project leverages cloud-based services to optimize data processing, enabling the handling of large image datasets efficiently. By utilizing distributed training, it accelerates the model training process across multiple computational resources, which is crucial for classifying images based on location scenes. This approach ensures scalability, faster model training, and enhanced performance in handling diverse and extensive datasets.

-----------------------------------------------
Steps to Setup Cloud Environment
-----------------------------------------------
**Step 1: Create a resource group**
* Log in to Azure Portal
* Navigate to Resource Groups: In the left-hand menu, select Resource Groups (or search for it in the search bar).
* Click the + Create button.
*	Resource Group Name: Enter a unique name.
* Review and Create: Review the details, click Review + Create, then click Create to finalize.
* Verify: Confirm the resource group is listed under Resource Groups.

**Step 2: Create Azure Storage Container**
* Navigate to Storage Accounts in Azure Portal and click Create.
* Provide a unique name to the storage conatiner.
* After the storage account is created, go to Containers under the storage account.
* Click + Container.

**Step 3: Set up Databricks Workspace**
* Create Azure Databricks Workspace
* Go to Azure Databricks in the Azure portal and click + Create.
* Select the resource group created earlier.
* Provide a workspace name (e.g., ImageClassificationDBW).
* Choose the appropriate pricing tier (e.g., Standard).
* Click Review + Create and then Create.
  
**Step 4: Set Up Databricks Cluster**
* Open the Databricks workspace.
* Go to Clusters and click + Create Cluster.
* Provide a name for the cluster (e.g., ImageClassificationCluster).
* Choose a runtime version with ML capabilities (e.g., Databricks Runtime 12.0 ML).
* Select the appropriate worker type (e.g., Standard_DS3_v2) and the number of workers.
* Click Create Cluster.

