# Application Documentation QA RAG App Using AWS

## Overview
This application utilizes machine learning models to process and analyze PDF documents. It features data ingestion, text splitting, embeddings generation, and a question-answering system, built using the LangChain library and AWS services.

## Video Demonstration
For a live demonstration of the application, check out this video on LinkedIn:
[Watch the Video](https://www.linkedin.com/feed/update/urn:li:ugcPost:7177989540987498499)

## Features
- **Data Ingestion**: Automatically loads PDF documents from a specified directory for processing.
- **Text Splitting**: Splits text from PDF documents into manageable chunks for better processing using the Recursive Character Text Splitter.
- **Embeddings Generation**: Utilizes the Titan Embeddings Model from Bedrock to generate text embeddings.
- **Question Answering**: Implements a question-answering system capable of retrieving information directly from the processed texts.

## Technology Stack
- **Python**: Main programming language.
- **Streamlit**: Used for creating the web interface.
- **Boto3**: AWS SDK for Python to interact with AWS services.
- **LangChain Community**: Provides tools for embeddings and document loaders.
- **FAISS**: For efficient similarity search and clustering of dense vectors.

## Setup and Installation
1. Ensure Python 3.x is installed on your system.
2. Install required libraries using `pip install -r requirements.txt` (ensure you create this file based on the libraries used in the script).
3. Configure AWS credentials to use Boto3.
4. Check `app.py` and fill the potion with `Needed` which are model id, can be choose from AWS.
5. Run the application by executing `streamlit run app.py` in your terminal.


## Usage
1. Place your PDF documents in the `data` directory.
2. Start the server using Streamlit and navigate to the provided local URL.
3. Interact with the application through the web interface to upload documents and ask questions based on the document contents.

## Contributing
Contributions are welcome. Please fork the repository, make your changes, and submit a pull request.

## License
MIT License



