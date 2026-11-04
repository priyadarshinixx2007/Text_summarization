# AI Text Summarization Using Python and Streamlit

## Project Overview

AI Text Summarization is a Python-based application that uses Artificial Intelligence and Natural Language Processing (NLP) to generate concise summaries from lengthy English text.

The application is developed using Streamlit and Hugging Face Transformers. It uses a pre-trained DistilBART model to understand the input text and produce a shorter version containing the essential information.

The project aims to make reading and understanding long passages easier by reducing unnecessary information while preserving the main ideas.

## Objectives

- To develop an AI-based text summarization application.
- To convert lengthy text into shorter and meaningful summaries.
- To identify important information from the given content.
- To provide different summary length preferences.
- To create a simple and interactive web interface using Streamlit.

## Technologies Used

- Python
- Streamlit
- Hugging Face Transformers
- PyTorch
- Natural Language Processing (NLP)
- DistilBART CNN/DailyMail Model

## Features

- User-friendly web application interface.
- AI-powered automatic text summarization.
- Multiple summary length options.
- Input text processing.
- Generation of meaningful and concise summaries.
- Display of original and summarized text statistics.
- Download option for the generated summary.
- Utilizes a pre-trained Hugging Face model.

## Project Structure

    TextSummarizerAI/
    |
    |-- app.py
    |-- requirements.txt
    |-- README.md
    |-- .gitignore

## Model Details

This project uses the pre-trained Hugging Face model:

`sshleifer/distilbart-cnn-12-6`

DistilBART is a Transformer-based language model designed for text summarization tasks. It processes English text and generates summaries by retaining the important information from the original content.

The model is based on the CNN/DailyMail summarization dataset.

## Installation and Setup

### 1. Install Python

Install Python 3.11 or Python 3.12 on your system.

Verify the installation:

    python --version

### 2. Create a Virtual Environment

    python -m venv .venv

Activate the virtual environment.

For Windows:

    .\.venv\Scripts\Activate.ps1

For macOS and Linux:

    source .venv/bin/activate

### 3. Install Required Libraries

    python -m pip install --upgrade pip
    python -m pip install -r requirements.txt

### 4. Launch the Application

    python -m streamlit run app.py

The Streamlit application can be accessed through the local URL displayed in the terminal.

## Working of the Application

1. The user enters a passage of English text.
2. The application accepts the input through the Streamlit interface.
3. The selected summary length is provided as a parameter.
4. The Hugging Face Transformer model processes the text.
5. The model generates a summarized version of the original content.
6. The summary and related statistics are displayed to the user.
7. The user can download the generated summary.

## Applications

- Summarizing educational materials.
- Understanding lengthy articles.
- Preparing short notes from paragraphs.
- Summarizing research content.
- Improving reading efficiency.
- Extracting important information from documents.

## Limitations

- The model mainly supports English-language summarization.
- Long input texts may exceed the model's token limit.
- The generated summary may not include every detail.
- The quality of the summary depends on the input text.
- Model execution requires sufficient system memory and processing resources.

## Future Enhancements

- Adding support for PDF and document uploads.
- Implementing multilingual text summarization.
- Adding more pre-trained summarization models.
- Improving the summarization of lengthy documents.
- Providing copy and download options.
- Deploying the application on a cloud platform.

## Conclusion

The AI Text Summarization project demonstrates the use of Artificial Intelligence, Natural Language Processing, and Transformer models for automatic text summarization.

By combining Python, Streamlit, and Hugging Face Transformers, the project provides a simple approach to converting lengthy text into concise and meaningful summaries. This application can be useful for students, researchers, and individuals who need to understand large amounts of textual information efficiently.

## Author

Developed as an Artificial Intelligence and Python project using Streamlit and Hugging Face Transformers.
