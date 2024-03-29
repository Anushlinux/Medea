Chat with Gemini and PDF Processing

This project demonstrates a chat application built with Streamlit that interacts with a large language model (LLM) and can process information from uploaded PDFs.

Features:

    Chat with the Gemini LLM using text queries.
    Upload and process text content from PDF files.
    The LLM response considers both the user's query and the uploaded PDF content.

Requirements:

    Python 3.x
    Streamlit (pip install streamlit)
    google-generativeai (pip install google-generativeai)
    pypdf (pip install pypdf)

Additional requirements listed in requirements.txt:

The requirements.txt file specifies additional libraries needed for the project's functionality. You can install them all using the following command:
Bash

    pip install -r requirements.txt


    API Key:

To use the Gemini LLM, you'll need a Google Cloud API key with access to the Generative AI service. Refer to the Google Cloud documentation for creating an API key: https://console.cloud.google.com/

Instructions:

    Configure your Gemini API key:
        Replace 'AAIzaSyBSul-Xy19E6MpXxa06ZdKQeJ9JgZ64Gl8' in the code with your actual API key.

    Run the application:
        Save the code in a Python file (e.g., chat_app.py).
        Open a terminal, navigate to the directory containing the file, and run:
    Bash

    streamlit run chat_app.py

    Use code with caution.

    Interact with the app:
        Type your question in the chat input box.
        Optionally, upload a PDF file for the LLM to consider along with your query.
        Click "Enter" or the chat icon to send your query.
        The LLM will respond based on your text and the uploaded PDF (if provided).

How it Works:

    The application initializes a chat session with the Gemini LLM.
    User queries and uploaded PDFs are processed through the llm_function.
    The function extracts text from the PDF (if uploaded) and combines it with the user's query.
    The combined text is sent to the LLM for generating a response.
    The LLM response is displayed in the chat history.

Further Enhancements:

    Implement functionalities to handle different file formats.
    Integrate error handling for invalid file uploads or API calls.
    Style the chat interface for a more user-friendly experience.

This is a basic structure for your README file. You can add more details about the project, screenshots, and explanations of the code functionalities for a more comprehensive guide.
