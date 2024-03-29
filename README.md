Chat with Gemini and PDF Processing


This is a Streamlit application that allows users to interact with PDF documents using natural language queries. The application leverages the Google Generative AI API (specifically, the Gemini-Pro model) to understand the user's queries and provide relevant responses based on the content of the uploaded PDF file.
Features

    Upload a PDF file to the application
    Ask natural language questions about the content of the PDF
    Receive contextual responses from the AI model
    Interactive chat interface to view the conversation history

Installation

    Clone the repository:

bash

git clone https://github.com/your-username/ai-powered-pdf-chat.git

    Install the required dependencies:

bash

pip install -r requirements.txt

    Set up the Google Generative AI API:
        Visit the Google Cloud Console and create a new project.
        Enable the Generative AI API for your project.
        Create an API key and replace "AAIzaSyBSul-Xy19E6MpXxa06ZdKQeJ9JgZ64Gl8" in the code with your own API key.

Usage

    Run the Streamlit application:

bash

streamlit run app.py

    Upload a PDF file by clicking the "Upload File" button.
    Enter your query in the chat input box and press Enter.
    The AI model will analyze the uploaded PDF and provide a relevant response based on your query.
    Continue the conversation by asking follow-up questions or providing new queries.

Dependencies

The project relies on the following key dependencies:

    streamlit: A Python library for building interactive web applications.
    google.generativeai: The Google Generative AI Python library for accessing the Generative AI API.
    pypdf: A library for extracting text from PDF files.

For a complete list of dependencies, please refer to the requirements.txt file.
Contributing

Contributions are welcome! If you find any issues or have suggestions for improvements, please open an issue or submit a pull request.
License

This project is licensed under the MIT License.

