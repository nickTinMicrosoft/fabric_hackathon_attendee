# Use Azure AI to Discover Intelligence in the Data (1 hour)

In this part of the hackathon, use Azure AI to uncover insights, patterns, or predictions from the data you ingested and transformed.

You can approach this however you want. The goal is to add intelligence to your dataset using any Azure AI capability.

## Ways You Can Add Intelligence

- Run text analytics: Use Azure AI Language to extract key phrases, detect sentiment, or identify named entities (people, places, products, and so on).
- Classify or tag data: Use a prebuilt model to categorize text, label documents, or assign topics.
- Summarize content: Feed your dataset into Azure OpenAI (or the Fabric Prompt Flow experience) to summarize reports, logs, or long text fields.
- Build a quick prediction model: Use AutoML in Fabric or Azure ML to predict churn, demand, volume, or yes/no outcomes.
- Generate insights with natural language: Let users ask questions about data and get plain-English answers using Azure OpenAI.
- Detect anomalies: Use Azure AI Anomaly Detector to find unusual spikes, drops, or outliers in time-series data.
- Enrich structured data: Use an LLM to rewrite messy text fields, normalize categories, or create derived columns.
- Create embeddings and similarity search: Generate embeddings with Azure OpenAI and find similar items, documents, or records.
- Analyze customer sentiment: If your data includes comments or notes, measure positive, negative, or neutral trends.
- Build a simple chatbot with Data Agent: Use your ingested dataset as context and build a Data Agent in Fabric.
- Enhance with AI Foundry: Connect your Data Agent in Azure AI Foundry as part of an agentic solution.

## Hackathon Note

You can do this entirely in Fabric or call Azure AI services directly. Both are valid. Fabric is faster to start, while Azure AI gives more control.

## Reference Paths

### 1. Natural-Language Q&A Over Your Data (Data Agent / Chat with Data)

| Option | What to use | Learn link |
| --- | --- | --- |
| Fabric | Data Agent on Lakehouse/Warehouse | [How to create a Data Agent](https://learn.microsoft.com/fabric/data-science/how-to-create-data-agent) |
| Azure AI | RAG with embeddings and chat using Azure OpenAI Service | [Use your data with Azure OpenAI](https://learn.microsoft.com/azure/ai-services/openai/use-your-data) |

### 2. Summarize, Classify, Sentiment, and Entities (Text Enrichment)

| Option | What to use | Learn link |
| --- | --- | --- |
| Fabric | AI Functions in notebooks / Prompt Flow | [AI Functions overview](https://learn.microsoft.com/fabric/data-science/ai-functions/overview) |
| Azure AI | Azure AI Language (Text Analytics) | [Azure AI Language overview](https://learn.microsoft.com/azure/ai-services/language-service/overview) |

### 3. Embeddings and Similarity Search

| Option | What to use | Learn link |
| --- | --- | --- |
| Fabric | AI Functions and vector index in Lakehouse | [AI Functions overview](https://learn.microsoft.com/fabric/data-science/ai-functions/overview) |
| Azure AI | Embeddings with Azure OpenAI | [Generate embeddings](https://learn.microsoft.com/azure/ai-services/openai/how-to/embeddings) |

### 4. Build a Prediction Model (AutoML)

| Option | What to use | Learn link |
| --- | --- | --- |
| Fabric | AutoML experiment on Lakehouse tables | [AutoML overview in Fabric](https://learn.microsoft.com/fabric/data-science/automl-overview) |
| Azure AI | AutoML in Azure ML | [AutoML in Azure Machine Learning](https://learn.microsoft.com/azure/machine-learning/automl/overview) |

### 5. Detect Anomalies in Time-Series

| Option | What to use | Learn link |
| --- | --- | --- |
| Fabric | Notebook with Python/Spark anomaly logic | [How to use notebooks in Fabric](https://learn.microsoft.com/fabric/data-engineering/how-to-use-notebook) |
| Azure AI | Azure AI Anomaly Detector | [Anomaly Detector overview](https://learn.microsoft.com/azure/ai-services/anomaly-detector/overview) |

### 6. Enrich and Normalize Messy Text Fields with LLMs

| Option | What to use | Learn link |
| --- | --- | --- |
| Fabric | Prompt Flow / AI Functions | [AI Functions overview](https://learn.microsoft.com/fabric/data-science/ai-functions/overview) |
| Azure AI | Azure OpenAI chat/completions | [How to work with chat models](https://learn.microsoft.com/azure/ai-services/openai/how-to/chatgpt) |

### 7. Agentic Extension (Advanced / Bonus)

| Option | What to use | Learn link |
| --- | --- | --- |
| Fabric | Data Agent as your data tool | [Data Agent concepts](https://learn.microsoft.com/fabric/data-science/concept-data-agent) |
| Azure AI | Connect to Azure AI Foundry for orchestration | [Use Microsoft Fabric data agent in Azure AI Foundry](https://learn.microsoft.com/azure/foundry/agents/how-to/tools/fabric) |

