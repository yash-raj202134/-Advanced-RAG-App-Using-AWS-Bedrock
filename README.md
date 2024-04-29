# Advanced RAG App using AWS Bedrock and LangChain

Welcome to the Advanced RAG App, a powerful application that leverages AWS Bedrock and LangChain to provide intelligent Retrieval Augmented Generation (RAG) capabilities. This application uses advanced natural language processing and machine learning techniques to help you analyze and interact with documents using large language models and AI services.

## Table of Contents

- [Overview](#overview)
- [Features](#features)
- [Prerequisites](#prerequisites)
- [Installation](#installation)
- [Usage](#usage)
- [License](#license)
- [Contributing](#contributing)
- [Contact](#contact)

## Overview

The Advanced RAG App allows users to upload PDF documents and interact with them using advanced AI models from AWS Bedrock and LangChain. This application supports:

- Generating embeddings and vectors from documents.
- Querying documents using large language models.
- Generating images using Stable Diffusion and AWS Bedrock.

## Features

- **Document Interaction**: Upload and interact with PDF documents.
- **Vector Embeddings**: Generate vector embeddings from documents.
- **Large Language Models**: Utilize large language models for document interaction.
- **Image Generation**: Generate images using Stable Diffusion and AWS Bedrock.
- **User-Friendly Interface**: Use Streamlit for an easy-to-use web interface.

## Prerequisites

- **Python 3.x**: Ensure you have Python 3.x installed.
- **AWS Account**: Set up an AWS account and configure access credentials.
- **Libraries**: The project requires various Python libraries, including:
    - `boto3`
    - `streamlit`
    - `FAISS`
    - `numpy`
    - `langchain`
    - Other libraries as required (refer to the `requirements.txt` file for details).

## Installation

1. **Clone the repository**:

    ```bash
    git clone <repository-url>
    ```

2. **Navigate to the project directory**:

    ```bash
    cd advanced-rag-app
    ```

3. **Install required dependencies**:

    ```bash
    pip install -r requirements.txt
    ```

4. **Configure AWS credentials**:

    Set up your AWS access credentials using the AWS CLI or by editing the `~/.aws/credentials` file.

## Usage

1. **Run the application**:

    ```bash
    streamlit run app.py
    ```

2. **Interact with the application**:

    - Upload your PDF documents and ask questions about them using the provided user interface.
    - Choose from different language models (Claude, Llama2) to interact with your documents.
    - Generate images based on textual prompts using AWS Bedrock and Stable Diffusion.

## License

This project is licensed under the Apache-2.0 License.

## Contributing

Contributions are welcome! Please fork this repository and submit pull requests for any features, improvements, or bug fixes.

## Contact

For any inquiries or support, please [contact us](mailto:yashraj3376@gmail.com).

Happy exploring!
