# PDFChatBot

PDFChatBot is an open-source Python project that allows you to build a chatbot for interacting with PDF documents. The chatbot extracts information from PDFs, performs text analysis, and answers questions without relying on any external APIs. This project utilizes open-source libraries and models.

## Features

- Extracts text content from PDF documents using an open-source PDF loader (PyPDF2).
- Splits documents into text snippets for efficient processing.
- Embeds text using pre-trained sentence embeddings (SBERT with MPNet).
- Utilizes pre-trained language models (T5 from the Flan model) for text generation and question-answering.
- Provides a flexible and modular structure for customization.

## Usage
Replace "YOUR_PDF_FILE_PATH" with the path to your PDF file.
Replace "YOUR_QUESTION" with the question you want to ask.



## Project Structure

- chat_bot.ipynb: Main script for the chatbot.
- PyPDFLoader.py: PDF loader using PyPDF2.
- text_splitter.py: Text splitting utilities.
- nembedding.py: Text embedding using SBERT with MPNet.
- vectorizer.py: Document vectorization using Chroma.
- flan_t5_base.py: Text generation using T5 from the Flan model.
  
