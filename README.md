This repository contains 2 Retrieval Augmented Generation (RAG) implementations:

#
# A) Retrieval Question Answering with Llama 2
#

This Jupyter notebook demonstrates how to set up a Retrieval Question Answering system using Llama 2, a large language model. The system retrieves relevant information from a set of documents and generates responses to user questions.

Prerequisites

Ensure you have the following Python packages installed:

pip install langchain langchain-community sentence_transformers faiss-cpu ctransformers huggingface-hub pypdf

Usage

* Run the notebook retrieval_qa_llama_2.ipynb

* Follow the instructions in the notebook to load documents, preprocess them, and set up the Llama 2 model for question answering.

* Use the provided functions to query the model with your questions and retrieve answers.

#
# B) RAG with Llama 3
# 

This Jupyter notebook demonstrates how to set up a Question Answering system using Llama 3, a state-of-the-art language model. The system utilizes a combination of document retrieval and generation to provide accurate answers to user queries.

Prerequisites

pip install langchain langchain-community sentence_transformers transformers accelerate faiss-cpu pypdf

Usage

* Run the notebook rag_llama3.ipynb.

* Load your documents using either PyPDFLoader or OnlinePDFLoader.

* Preprocess the documents and split them into chunks for efficient processing.

* Set up the Llama 3 model for question answering.

* Use the provided functions to query the model with your questions and retrieve answers.


# References
* Llama 2 GitHub Repository
* Sentence Transformers Documentation
* FAISS Documentation
