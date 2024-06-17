# Q&A Chatbot

This project is a Q&A chatbot utilizing the Gemini API. It provides an interactive interface for users to ask questions and receive answers from the Gemini AI model, including image analysis capabilities. The project includes multiple scripts to demonstrate different functionalities.

## Table of Contents
- [Installation](#installation)
- [Setup](#setup)
- [Usage](#usage)
- [Files Description](#files-description)
- [Acknowledgments](#acknowledgments)

## Installation

To get started, clone the repository and install the required dependencies.

```bash
git clone https://github.com/yourusername/gemini-qachat.git
cd gemini-qachat
pip install -r requirements.txt
```
## Setup

## API Key Configuration:
1. Obtain your API key from the Google Cloud Console.
2. Create a `.env` file in the project root directory and add your API key:


## Environment Variables:
- Load environment variables by ensuring the python-dotenv package is installed and `.env` file is properly configured.

# Usage
You can run the Streamlit applications using the following commands:

- **Vision Q&A Chatbot:**
```bash
streamlit run vision.py

streamlit run app.py

streamlit run chat.py

streamlit run qachat.py 
```
# Project Overview

This project contains several Python scripts that interface with the Gemini Vision API for various purposes. Each script serves a distinct function in enhancing user interaction with the AI.

## Files

### vision.py

Interface for uploading an image and asking questions. Uses Gemini Vision API for text and image input responses.

**Key Features:**
- Text input for questions.
- Image upload functionality.
- Integration with Gemini Vision model.

### app.py

Simple Q&A interface using the Gemini API. Users can input questions and receive text-based responses.

**Key Features:**
- Text input for questions.
- Integration with Gemini model.

### chat.py

Extends Q&A functionality with chat history. Users can have interactive conversations with AI.

**Key Features:**
- Text input for questions.
- Chat history display.
- Integration with Gemini model.

### qachat.py

Comprehensive chat interface with session state management. Maintains chat history across interactions.

**Key Features:**
- Text input for questions.
- Session state management for chat history.
- Integration with Gemini model.

## Acknowledgments

- Google Cloud for providing the Gemini API.
- Streamlit for providing an easy-to-use web app framework.

## Contributing

Feel free to contribute to this project by creating issues, suggesting features, or submitting pull requests. Your contributions are welcome!

