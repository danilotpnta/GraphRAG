# GraphRAG
Exploring creation of Knowledge Graphs from unstructured text

## Setup
Create a conda environment with the required dependencies:

```bash
conda create -n graphrag python=3.11 -y
conda activate graphrag
pip install -r requirements.txt
```

For the construction of the knowledge graph, we need to configure the API keys for OpenAI or Azure OpenAI. You can set up these keys in the following [`.env`](.env) file:

```bash
AZURE_OPENAI_API_KEY=your-key
AZURE_OPENAI_ENDPOINT=https://your-resource.openai.azure.com
AZURE_OPENAI_DEPLOYMENT_NAME=your-deployment-name
AZURE_OPENAI_API_VERSION=2024-02-15-preview
```
