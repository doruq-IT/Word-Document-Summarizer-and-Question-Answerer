# Word Document Summarizer

Welcome to the Word Document Summarizer – a powerful Python application that harnesses the magic of Natural Language Processing (NLP) to simplify your document management tasks.

## Overview

Managing lengthy Word and PDF documents can be a daunting task, but our Word Document Summarizer is here to save the day. Whether you're a student trying to extract key insights from a research paper or a professional looking to quickly grasp the essence of a lengthy report, our tool has got you covered.

## Features

- **Document Summarization**: Upload Word (.docx) or PDF (.pdf) documents and let our application generate concise summaries for you.
- **Smart Question-Answering**: Have a question about the content? Just ask, and our application will provide you with answers extracted from the document.
- **User-Friendly Interface**: Our sleek and intuitive graphical interface built with tkinter makes document management a breeze.

## Getting Started

1. **Clone the Repository**:

   ```bash
   git clone https://github.com/doruq-IT/word-document-summarizer.git
   
2. **Install Dependencies**:
  pip install tkinter docx pdfplumber transformers torch

3. **Start Simplifying Your Documents**:
  Upload your document.
  Summarize it with a single click.
  Ask questions, and get instant answers.

5. **Installation**:
   pip install -r requirements.txt

## Usage Example:
  Upload a Word document
    upload_file_path = filedialog.askopenfilename(filetypes=[("Word Document", ".docx"), ("PDF Document", ".pdf")])

  **Summarize the document**
    summarize_document(upload_file_path)

  **Ask a question about the document**
    question = "What is the main topic of this document?"
    answer = ask_question(upload_file_path, question)

  **Print the answer**
    print(answer)

  **Contributions**:
    Contributions are welcome! Please open an issue or a pull request to share your feedback or suggestions.
    
## Requirements:
  Python 3.8+
  Transformers
  Docx
  Pdfplumber
  Tkinter
  
## Additional Information:

This project was created by doruq-IT.

## Contact:

If you have any questions or concerns, please contact okan.rescue@gmail.com.

## Here are some additional tips for writing a README that will grab attention:
  Start with a strong title and description that clearly states what the project is about.
  Highlight the key features of the project in the description.
  Use clear and concise language that is easy to understand.
  Include screenshots or videos to show off the project.
  Use a call to action to encourage users to try the project.

# git
