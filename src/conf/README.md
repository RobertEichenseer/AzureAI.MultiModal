# App Configuration

## Folder Content

| File | Content | Details |
|---|---|---|
| ./configuration.env | application configuration | Apikeys, endpoints and connection string necessary to execute the sample app. The file will be automatically created by executing [this](../create_env/CreateEnv.azcli) Azure CLI script |
| ./configuration.env.example | application configuration | If you prefer to use existing and already deployed Azure services than please provide the necessary apikey, endpoint and storage connection string information in this file and rename it to `configuration.env` |

## Necessary configuration

- ***AI.VISION.APIKEY***: Apikey for a deployed Azure AI Vision instance
- ***AI.VISION.ENDPOINT***: Endpoint of a deployed Azure AI Vision instance
- ***AI.STORAGE.CONNECTIONSTRING***: Storage connection string. The Azure Blob storage will be used to upload architecture diagrams / sketches
- ***AI.SEARCH.APIKEY***: Apikey for a deployed Azure AI Search (aka Cognitive Search) instance
- ***AI.SEARCH.ENDPOINT***: Endpoint of a deployed Azure AI Search (aka Cognitive Search) instance.
