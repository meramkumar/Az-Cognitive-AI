# Az-Cognitive-AI

Welcome to learn Azure Cognitive Services and there ability.

Pre-Config

Step 1:
Create a storage account in Azure portal/follow documentation available <a href='https://docs.microsoft.com/en-us/azure/storage/common/storage-account-create?tabs=azure-powershell'>Click Here</a>

PS Command

Connect-AzAccount
New-AzStorageAccount -ResourceGroupName $resourceGroup `
  -Name <account-name> `
  -Location $location `
  -SkuName Standard_RAGRS `
  -Kind StorageV2

Note:- For the example we can use LRS, StorageV2.

Step 2:
Upload atleast 100 different file types (docx, pdf, doc) in the root of the storage account.