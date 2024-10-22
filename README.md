Conversational RAG with PDF Uploads and Chat History
Overview
This project implements a Retrieval-Augmented Generation (RAG) model using Streamlit to create an interactive question-answering assistant. Users can upload PDF documents, which are processed to enable the assistant to answer questions based on the content of the uploaded files.

Features
PDF Uploading:
Upload one or more PDF files.
Interactive Chat Interface:
Ask questions related to the content of the uploaded PDFs.
Contextual Understanding:
The assistant uses chat history to rephrase questions, ensuring accurate responses.
Integration with Language Models:
Leverages advanced language models (e.g., ChatGroq) for generating responses based on the retrieved context. 
Technologies Used
Streamlit: For creating the web application interface.
LangChain: For building the RAG model and managing document retrieval.
Hugging Face: For embedding generation and language model integration.
Chroma: For managing the vector store and efficient document retrieval.
Installation
To run this project locally, clone the repository and install the required packages:
  git clone https://github.com/Alaaibrahim2/a.git
 cd a
 pip install -r requirements.txt




Usage
Run the Streamlit application:
bash
Copy code
streamlit run app.py
Upload PDF Files:
Use the upload feature to add your PDF documents.
Ask Questions:
Start interacting with the assistant by typing your questions related to the content of the uploaded PDFs





Example Interaction
User: What is the main topic of the uploaded document?
Assistant: The main topic of the document is about advancements in artificial intelligence.

