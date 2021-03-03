# arm-templates

## Standalone Template
### az deployment group create --name stroageadd --resource-group chetan-synechron --template-file storage.json 
## Parametrized Template
### az deployment group create --name pmstorage --resource-group chetan-synechron --template-file parameter.json --parameters strgName=synelab1001
