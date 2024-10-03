# LangChain & OpenAI Example Project

## Overview

This project is a simple example demonstrating the use of LangChain and OpenAI for retrieving and generating text-based answers based on a set of documents. The project primarily utilizes OpenAI's GPT-3.5-turbo model, along with a document retrieval system powered by Chroma and OpenAI embeddings.

## Features

- **Document Embeddings:** Uses OpenAI embeddings to convert documents into vectors for similarity search.
- **Retrieval System:** Employs Chroma to perform similarity searches against embedded documents.
- **Language Model:** Utilizes OpenAI's GPT-3.5-turbo for generating responses based on retrieved documents.
- **Prompting System:** Uses LangChain's template system for structuring prompts to the language model.

## Setup and Usage

### Installation

Make sure to install the necessary Python packages. You can typically do this with pip:

```bash
pip install langchain langchain-extras openai
```

### Environment Variables

Ensure you have a `.env` file or set the necessary environment variables for OpenAI and other services you might be using.

### Running the Script

Execute the main script to see the output for a given sample question:

```bash
python main.py
```

The script is designed to answer the question "tell me about cats" using the provided set of documents.

## License

This project is licensed under the MIT License.
