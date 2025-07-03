# **Building an AI-Powered RAG Assistant with LangChain**

## 📌 **Project Overview**  
This project implements a Retrieval-Augmented Generation (RAG) chatbot that helps query large volumes of documents. The chatbot leverages LangChain and Hugging Face's transformers to provide accurate, context-aware responses based on uploaded PDF documents.

## 🎯 **Key Features**
- **Document Processing**: Handles PDF documents using LangChain's document loaders
- **Text Chunking**: Implements intelligent text splitting for optimal processing
- **Vector Storage**: Uses Chroma DB for efficient storage and retrieval of document embeddings
- **Question Answering**: Leverages FLAN-T5-Large model for generating responses (more powerful models can be used based on resources)
- **User Interface**: Provides a clean Gradio interface for document upload and querying

## 🛠 **Technologies & Tools Used**
- **Python**
  - LangChain: Document processing and RAG pipeline
  - Hugging Face Transformers: FLAN-T5-Large for text generation
  - Sentence Transformers: Document embedding
  - ChromaDB: Vector storage
  - Gradio: Web interface
- **Models**:
  - FLAN-T5-Large: Main language model
  - all-MiniLM-L6-v2: Embedding model

## 💻 **Implementation Details**
- **Document Processing**: Uses PyPDFLoader for reading PDF files
- **Text Splitting**: Implements RecursiveCharacterTextSplitter for optimal chunk sizes
- **Embedding**: Utilizes Sentence Transformers for document vectorization
- **Retrieval System**: Implements similarity-based document retrieval
- **QA Chain**: Combines document retrieval with LLM-based answer generation
- **Web Interface**: Simple upload-and-query interface using Gradio

## 🚀 **Getting Started**
1. Ensure you have a Hugging Face API key in your environment
2. Install required dependencies
3. Run the Jupyter notebook
4. Access the interface at http://127.0.0.1:7860
5. Upload a PDF and start asking questions!
