# LLM-based Retrieval-Augmented Generation (RAG) Agent

## Overview

This repository contains the implementation of a Retrieval-Augmented Generation (RAG) agent utilizing a Large Language Model (LLM). The agent effectively manages user queries related to INSAT and computer science universities in Tunisia by retrieving relevant information from a ChromaDB vector database and performing web searches for out-of-domain queries.

## Key Features

- **ChromaDB Integration**: Efficient retrieval of domain-specific knowledge.
- **Web Search Functionality**: Fallback mechanism for out-of-scope queries.
- **LangGraph Routing**: Intelligent decision-making for query handling and hallucination management.

## Getting Started

### Prerequisites

Ensure you have the following installed:

- Python 3.x

- Acquire llama3 model permission from the Hugging Face model hub:
(https://huggingface.co/meta-llama/Meta-Llama-3-8B)
- Acquire a hugging face token from your profile settings (to use later in the code)

```bash
### Installation

Clone the repository:

```bash
git clone https://github.com/Zairi-Maissene/adaptive-rag-agent.git
cd adaptive-rag-agent
```

That's it! Run the notebook and test the agent :smiley: .

