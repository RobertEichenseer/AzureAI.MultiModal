# Demo App

## Overview / Content

- [Polyglot Notebook](./MultiModalSample.ipynb) with end-to-end sample. Processing steps:
  - ***Install necessary nuget packages*** (DotNetEnv, Azure.Search.Documents & Azure.Storage.Blobs) and read application configuration.
  - **Import Helper Class***. The helper class provides simplified abstractions to:
    - Create an image embedding by crafting and executing a http call to the AI Vision REST endpoint.
    - Create an text embedding by crafting and executing a http call to the AI Vision REST endpoint.
    - Upload images to Azure Blob storage and creating a SAS
    - Create a search index in Azure AI Search
    - Store embeddings in Azure AI Search
    - Query Azure AI Search based on embedding
  - ***Processing***:
    - Create search index in Azure AI Search
    - Upload architecture sketches to Azure Blob Storage
    - Create image embeddings using Azure AI Vision
    - Store image embeddings in Azure AI Search
  - ***Query***:
    - Create a text embedding based on the search phrase
    - Perform search using Azure AI Search

