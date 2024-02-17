# Lab 6 - Chat with PDF

## Overview
This app is an AI Resume feedback bot, you can upload resume and get feedback
app.py: main script for the assistant app using LLM

## How to run it
1. `python -m venv venv`
1. `venv\Scripts\Activate.ps1`( for windows system)
1. `pip install -r requirements.txt`
1. `cp .env.sample .env`
1. Change the `.env` file to match your environment
1. `streamlit run app.py`

## Lessions Learned
- How can I provide feedback while processing tasks like file upload or API requests?
    - Utilize st.spinner to show loading messages or use st.progress for tasks with measurable progress.
- How do I handle errors gracefully?
    - Implement try-except blocks to catch and handle exceptions. Use st.exception to display error messages in the Streamlit app.
- How do I handle different file types for upload?
    - Depending on the file type, use appropriate libraries or methods for data extraction. Validate file types before processing.
## Future development
Consider breaking down the code into smaller, modular functions or classes for better readability and maintainability.Enhance error handling by providing more informative error messages to users and logging errors for debugging.Ensure secure handling of user data and sensitive information. Regularly update dependencies to patch security vulnerabilities.
