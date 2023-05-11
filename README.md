# Ask your PDF 💬

A Streamlit application that extracts text from a PDF file and answers questions based on the extracted text.

## Description

This Python script utilizes several libraries and modules to create a Streamlit application for processing PDF files. It extracts text from the uploaded PDF, splits it into chunks, and builds a knowledge base for question answering. Users can ask questions about the PDF content, and the application provides answers based on the extracted text.

## Features

- Upload PDF files to extract text from them.
- Perform text extraction and chunking for efficient question answering.
- Utilize OpenAI embeddings for text processing.
- Use a question-answering chain for answering user questions.
- Display answers in the Streamlit app interface.

## Installation

1. Clone the repository:

 
   ```git clone https://github.com/your-username/your-repository.git```
   
2. Change to the project directory:

```cd your-repository```

3. Create a virtual environment (optional but recommended):

```
python -m venv venv
source venv/bin/activate
```
4. Install the required dependencies:

    ```pip install -r requirements.txt```

Usage
  1. Make sure you have activated the virtual environment (if created).
  2. Run the script:
      ```python script.py```
  
  3. Open your web browser and navigate to the provided local URL (e.g., http://localhost:8501).

  4. Upload a PDF file using the file uploader in the Streamlit app.

  5. Enter your question about the PDF content in the provided text input.

  6. View the answer displayed in the app interface.

License
MIT License

Acknowledgments
https://streamlit.io/  Streamlit - The web application framework used for building the user interface.
https://github.com/mstamy2/PyPDF2 PyPDF2 - A library for reading PDF files.
https://openai.com/ OpenAI - The language model and embeddings used in the script.
https://github.com/langchain/langchain langchain - The library for text splitting, embeddings, vector stores, and question answering.
