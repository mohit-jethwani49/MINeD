# Document-Based Query Answering System README

Welcome to the Document-Based Query Answering System! This project allows users to input documents of various formats such as PDF, LaTeX, Word, and PowerPoint, along with a query, and retrieves relevant answers based on the content of the document.

## Overview

The Document-Based Query Answering System leverages the Gemini API provided by Google's Generative AI platform to analyze documents and generate responses to user queries. It is designed to be user-friendly and efficient, providing accurate answers from diverse document types.

## Dependencies

Below are the dependencies required to run this Flask project:

- `Flask`: A micro web framework for Python.
- `render_template`: A Flask module for rendering HTML templates.
- `request`: A Flask module for handling HTTP requests.
- `jsonify`: A Flask module for JSON response generation.
- `session`: A Flask module for managing user sessions.
- `os`: A Python module for interacting with the operating system.
- `fitz`: Python library for interacting with PDF files using the PyMuPDF library.
- `langchain_google_genai`: Python library for interfacing with Google's Generative AI platform.
- `google.generativeai`: API for accessing the Gemini model from Google's Generative AI platform.
- `pptx`: Python library for working with PowerPoint files.
- `aspose.pdf`: Python library for working with PDF files using the Aspose API.
- `docx`: Python library for working with Word documents.

## Installation

You can install these dependencies using pip, the Python package manager. Run the following command in your terminal or command prompt:

```bash
pip install Flask fitz langchain_google_genai pptx aspose.pdf docx
```
## Usage

To use this Flask project, follow these steps:

### 1. Install Dependencies

Make sure you have Python and pip installed on your system. Then, install the required dependencies using the following command:

### 2. Run the Flask Application

Start the Flask application by running the following command:
```terminal
python app.py
```

By default, the application will be served at `http://localhost:5000`.

### 4. Access the Application

Open your web browser and navigate to `http://localhost:5000` to access the application.

### 5. Interact with the Application

Once the application is running, you can interact with it using the provided features. For example:

- Fill out forms.
- Upload files.
- Click on buttons or links.

### 6. Explore the Codebase

Feel free to explore the codebase to understand how the application works. Here are some key directories and files you may want to look at:

- `app.py`: The main entry point of the Flask application.
- `templates/`: Directory containing HTML templates used by the application.


