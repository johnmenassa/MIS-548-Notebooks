# MIS-548-Notebooks
Codes and notebooks completed during my Deep Learning grad course. From LLM, data processing and text embedding generation, vector embeddings
README for Vector Embeddings and Search Notebook
Overview
This Jupyter notebook demonstrates the application of Large Language Models (LLMs) and vector databases to process and search text data efficiently. The notebook uses the Hugging Face transformers and sentence_transformers libraries to generate embeddings for a dataset, with faiss-cpu handling the vector search operations. It is a valuable resource for learning how to manage dense vector spaces and improve search functionalities in natural language processing tasks.

Prerequisites
To run this notebook, you will need:

Python 3.x
Jupyter Notebook or Jupyter Lab environment
Installation
Before running the notebook, ensure that all required libraries are installed. You can install them using the following pip commands:

bash
Copy code
pip install -U git+https://github.com/huggingface/transformers.git
pip install -U git+https://github.com/huggingface/accelerate.git
pip install faiss-cpu==1.7.4 sentence_transformers
Usage
Clone the repository or download the notebook file to your local machine.
Open the notebook in Jupyter Notebook or Jupyter Lab.
Run the cells sequentially to observe the process of loading data, generating embeddings, and performing vector searches.


