# MultiPDF Chat App

## Introduction

The MultiPDF Chat App is a Python-based application designed to facilitate interaction with multiple PDF documents through a chat interface. You can pose questions in natural language, and the app will generate relevant responses based on the content of the PDFs. The app leverages an advanced language model to ensure accurate answers.

## How It Works

The application follows a series of steps to generate responses:

1. **PDF Loading:** The app reads multiple PDF documents and extracts their text content.
2. **Text Chunking:** The extracted text is divided into smaller, manageable chunks.
3. **Language Model:** The application uses a language model to create vector representations (embeddings) of the text chunks.
4. **Similarity Matching:** The app compares your questions with the text chunks to identify the most semantically similar ones.
5. **Response Generation:** The selected chunks are passed to the language model, which generates a response based on the relevant content of the PDFs.

## Dependencies and Installation

To install the MultiPDF Chat App, follow these steps:

1. Clone the repository to your local machine.
2. Install the required dependencies by running:
   ```sh
   pip install -r requirements.txt

   ```

3. Obtain an API key from OpenAI and add it to the `.env` file in the project directory.
```commandline
OPENAI_API_KEY=your_secrit_api_key
```

## Usage
-----
To use the MultiPDF Chat App, follow these steps:

1. Ensure that you have installed the required dependencies and added the OpenAI API key to the `.env` file.

2. Run the `main.py` file using the Streamlit CLI. Execute the following command:
   ```
   streamlit run app.py
   ```

3. The application will launch in your default web browser, displaying the user interface.

4. Load multiple PDF documents into the app by following the provided instructions.

5. Ask questions in natural language about the loaded PDFs using the chat interface.

## Contributing
------------
This repository is intended for educational purposes and does not accept further contributions. It serves as supporting material for a YouTube tutorial that demonstrates how to build this project. Feel free to utilize and enhance the app based on your own requirements.


