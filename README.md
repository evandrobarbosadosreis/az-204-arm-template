# AZ-204ARM Template

Exemplo de utilização de um Azure Resource Manager Template para publicação de um conjunto de recursos através do Azure CLI.

# Processo de publicação

1. Login na sua conta Azure

    `az login`

2. Criação de um Resource Group

    `az group create --name meu-rss-group --location eastus2`

3. Deploy dos recursos

    `az deployment group create --name meu-deploy --resource-group meu-rss-group --template-file arm.template.json --parameters arm.template.parameters.json`

