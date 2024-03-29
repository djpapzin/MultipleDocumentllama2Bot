
# MultipleDocumentllama2Bot 📚

Welcome to the `MultipleDocumentllama2Bot` repository. This project provides a chatbot that can answer questions based on multiple uploaded documents. It utilizes the `llama2` model for conversational retrieval and supports various document formats including `.pdf`, `.docx`, `.doc`, and `.txt`.

![Demo Image](demo.jpeg)

## Features

- **Document Upload**: Easily upload multiple documents in various formats.
- **Conversational Interface**: Engage with the chatbot and ask questions related to the content of the uploaded documents.
- **Powered by llama2**: Receive accurate and context-aware answers generated by the `llama2` model.
- **Multiple File Support**: Seamlessly supports `.pdf`, `.docx`, `.doc`, and `.txt` file formats.

## Demo

Try out the live demo here: [MultipleDocumentllama2Bot Demo](https://multipledocumentllama2bot.streamlit.app/)

## Prerequisites

Before you begin, ensure you have met the following requirements:

- Python 3.x
- Git (if cloning the repository)

## Installation & Setup

1. **Clone the Repository**:
   ```bash
   git clone https://github.com/djpapzin/MultipleDocumentllama2Bot
   ```

2. **Navigate to the Project Directory**:
   ```bash
   cd MultipleDocumentllama2Bot
   ```

3. **Install the Required Packages**:
   ```bash
   pip install -r requirements.txt
   ```

4. **Set Up Your `.env` File**:
   - Obtain your `REPLICATE_API_TOKEN` from [Replicate](https://replicate.com/account/api-tokens).
   - Add the token to your `.env` file.

## Usage

1. **Run the Streamlit App**:
   ```bash
   streamlit run app.py
   ```

2. **Access the App**: Navigate to the provided URL in your browser.

3. **Upload & Interact**:
   - Upload your documents using the sidebar.
   - Ask questions related to your documents in the chat interface.

## Contributing

We welcome contributions! If you'd like to contribute, feel free to fork the repository, make your changes, and submit a pull request. For major changes, please open an issue first to discuss what you would like to change.

## License

This project is licensed under the MIT License. Please see the `LICENSE.md` file for more details.