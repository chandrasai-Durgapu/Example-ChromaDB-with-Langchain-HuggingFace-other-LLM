# Example ChromaDB + LangChain + HuggingFace / Other LLMs 🎯

This repository demonstrates how to integrate **ChromaDB** (vector database) with **LangChain**, **HuggingFace models**, or other LLMs, by walking through a working example in a Jupyter Notebook.

The GitHub repository chandrasai-Durgapu/Example-ChromaDB-with-Langchain-HuggingFace-other-LLM
 demonstrates the integration of ChromaDB, LangChain, and Hugging Face models for building a semantic search and question-answering system using text data.

The notebook `Copy_of_chromadb1_CLEAN.ipynb` serves as the core of the example, showing ingestion of documents, embedding, retrieval, and question answering pipelines.

---
## Project Overview

This project showcases how to:

Embed Text Data: Utilize Hugging Face's ALL Mini LM L6 v2 model to generate embeddings for text data.

Store Embeddings: Employ ChromaDB to store and manage these embeddings efficiently.

Retrieve Information: Implement LangChain to facilitate semantic search and question-answering capabilities.

Integrate LLMs: Incorporate large language models like LLaMA and OpenAI's models for advanced processing.

The repository includes a Jupyter Notebook (Copy_of_chromadb1_CLEAN.ipynb) that provides a step-by-step guide on setting up and utilizing these tools.
---

## 🧩 Contents

- `Copy_of_chromadb1_CLEAN.ipynb` — a cleaned, documented notebook that shows the end-to-end example  
- (Optional future) Python modules / utilities for data ingestion, embeddings, querying  

---

## 🚀 How to Run

### Prerequisites

- Python 3.8+
- Jupyter / IPython environment  
- Install these (or similar) packages:

```bash
pip install chromadb langchain transformers torch
```
---
### Clone the Repository
```bash
git clone https://github.com/chandrasai-Durgapu/Example-ChromaDB-with-Langchain-HuggingFace-other-LLM.git
cd Example-ChromaDB-with-Langchain-HuggingFace-other-LLM
```
---
## Set Up a Python Environment:

It's recommended to use a virtual environment:
```bash
python -m venv venv
source venv/bin/activate  # On Windows, use `venv\Scripts\activate`
```
---
### Launch the notebook:
```bash
jupyter notebook Copy_of_chromadb1_CLEAN.ipynb
```
---
## Use Cases

This setup is ideal for:

Document Search Engines: Implementing efficient search capabilities over large text corpora.

Chatbots and Virtual Assistants: Creating systems that can answer questions based on specific documents or datasets.

Research Tools: Developing applications that assist in retrieving relevant information from academic papers or technical documents.
