Sample code to manipulate and play around with Azure Key Vault


1)Create a key vault in Azure portal. During creation in access configuration/policies section make sure to click on 'Vault access policy' instead of the recommended Azure RBAC if you don't have RCAB setup

I didn't have RBAC setup hence selected the 2nd option(vault access policy).

2) Create a quick start maven project and in the main method copy paste the code from this repo.


Replace with your key vault name and you are ready to run it.

Reference - https://learn.microsoft.com/en-gb/azure/key-vault/secrets/quick-create-java?tabs=azure-cli
