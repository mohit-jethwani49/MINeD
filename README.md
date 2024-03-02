# Document-Based Query Answering System README

Welcome to the Document-Based Query Answering System! This project allows users to input documents of various formats such as PDF, LaTeX, Word, and PowerPoint, along with a query, and retrieves relevant answers based on the content of the document.

## Overview

The Document-Based Query Answering System leverages the Gemini API provided by Google's Generative AI platform to analyze documents and generate responses to user queries. It is designed to be user-friendly and efficient, providing accurate answers from diverse document types.

## Dependencies

Ensure you have the following dependencies installed in your environment:

- `langchain_google_genai`: Python library for interfacing with Google's Generative AI platform.
- `google.generativeai as genai`: API for accessing the Gemini model from Google's Generative AI platform.
- `fitz`: Python library for interacting with PDF files using the PyMuPDF library.
- `PyMuPDF`: Python bindings for the MuPDF library, enabling PDF manipulation.
- `frontend`: Frontend interface components for user interaction.

You can install these dependencies via pip:

```bash
pip install langchain_google_genai google.generativeai fitz PyMuPDF frontend
```

## Usage

1. **Setup Google API Key**: Obtain a Google API key and set it as an environment variable named `GOOGLE_API_KEY`.

2. **Input Document**: Upload a document of supported formats (.pdf, .tex, .doc, .ppt) containing relevant information.

3. **Enter Query**: Type your query into the provided input field.

4. **Retrieve Answers**: The system will process the document and provide relevant answers based on the query.

## Contributors

- [Your Name] - Project Lead & Developer
- [Contributor 1] - Developer
- [Contributor 2] - Developer

