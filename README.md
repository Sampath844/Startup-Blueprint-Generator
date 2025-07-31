# Retrieval Augmented Generation (RAG) with Langchain

This project demonstrates how to build a Retrieval Augmented Generation (RAG) pipeline using Langchain and IBM Granite models. The notebook guides you through setting up a knowledge base, creating embeddings, storing them in a vector database, and generating business blueprints for startup ideas using a large language model.

## Features
- **RAG Pipeline**: Combines retrieval of relevant knowledge with generative AI for enhanced responses.
- **IBM Granite Models**: Utilizes IBM's Granite embedding and LLM models via Huggingface and Replicate.
- **Vector Database**: Uses Milvus (or FAISS for demonstration) to store and retrieve document embeddings.
- **Business Blueprint Generator**: Interactive UI to generate comprehensive startup blueprints from user ideas.
- **Sample Knowledge Sources**: Loads and processes business-related documents and PDFs.

## Getting Started

### Prerequisites
- Python 3.10, 3.11, or 3.12
- Jupyter Notebook or VS Code with Jupyter support

### Installation
1. Clone this repository or download the notebook file.
2. Install required dependencies by running the following in a notebook cell:
   ```python
   %pip install git+https://github.com/ibm-granite-community/utils \
       transformers \
       langchain_community \
       'langchain_huggingface[full]' \
       langchain_milvus \
       replicate \
       wget \
       pypdf \
       tiktoken \
       faiss-cpu
   ```
3. (Optional) Set up your Replicate API token as an environment variable for LLM access.

### Usage
1. Open `RAG_with_Langchain.ipynb` in Jupyter or VS Code.
2. Follow the notebook cells step by step:
   - Set up the environment and install dependencies.
   - Configure embedding and LLM models.
   - Load and process knowledge sources.
   - Build the vector database.
   - Use the interactive UI to generate business blueprints from your startup ideas.

## Project Structure
- `RAG_with_Langchain.ipynb` — Main notebook with code, explanations, and UI.
- `STARTUP KNOWLEDGE BASE.docx` — Example knowledge base document.
- Other files: Certificates, presentations, and PDFs for reference.

## References
- [IBM Granite Models on Huggingface](https://huggingface.co/ibm-granite)
- [Langchain Documentation](https://python.langchain.com/)
- [Milvus Vector Database](https://milvus.io/)
- [Replicate API](https://replicate.com/)

## License
This project is for educational and demonstration purposes. See individual libraries for their respective licenses.
