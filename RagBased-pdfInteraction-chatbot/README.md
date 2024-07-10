# Data-Science-Decoder-Bot
## Interactive RAG-based LLM for Multi-PDF Document Analysis

## Introduction

This project is a Streamlit-based application that allows users to interact with a conversational AI model to answer questions based on the content of multiple PDF files. 

## Key Features:

* **PDF File Upload:** Upload and analyze multiple PDF documents.
* **Text Extraction:** Efficiently extract text content from PDFs.
* **Text Chunking:** Break down extracted text for optimized vector storage.
* **Vector Store Creation:** Generate embeddings and store them in a FAISS vector store for fast retrieval.
* **Question Answering:** Ask questions, retrieve relevant text snippets, and receive informative responses.

## Technologies Used

* **Streamlit:** Build interactive web apps in Python.
* **PyPDF2:** Extract text from PDF documents.
* **LangChain:** Framework for building LLM applications.
* **Google Generative AI:** Pre-trained language models for text understanding.
* **FAISS:** Efficient similarity search library for dense vectors.

## Installation

1. **Clone the Repository:**

   ```bash
   git clone https://github.com/your-username/data-science-decoder-bot.git
   ```

2. **Install Dependencies:**

   ```bash
   pip install -r requirements.txt
   ```

3. **Set Google API Key:**

   Create a Google Generative AI API key and set the `GOOGLE_API_KEY` environment variable.

4. **Run the App:**

   ```bash
   streamlit run chatpdf1.py
   ```

## Usage

1. Upload the data science PDF files using the sidebar uploader.
2. Click "Submit & Process" to analyze the uploaded PDFs.
3. Once processing is complete, ask questions in the text input field.
4. The application will respond based on the analyzed document content.



## Future Improvements

* Support for additional file formats (Word, Excel, PowerPoint).
* Enhanced user interface with features like:
    * View original PDFs.
    * Highlight relevant text snippets.
    * Save conversation history.
* Explore alternative language models or fine-tuning for domain-specific tasks.
* Implement more advanced question-answering capabilities with follow-up questions and detailed explanations.

