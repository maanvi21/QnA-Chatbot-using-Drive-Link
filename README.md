# QnA Chatbot Using Drive Link

## Overview
This project is a QnA Chatbot that utilizes Google Drive for storing and retrieving information. It allows users to ask questions, and the chatbot responds with answers derived from the content stored in Drive.

## Features
- **Natural Language Processing:** Understands user questions and provides relevant answers.
- **Integration with Google Drive:** Easily access and manage documents and data stored in Google Drive.
- **User-friendly Interface:** Simple and intuitive interface for interacting with the chatbot.
- **Customizable Responses:** Ability to tailor the bot's responses based on user needs.

## Installation
To install the project, follow these steps:
1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/QnA-Chatbot-useing-Drive-Link.git
   ```
2. Navigate into the cloned directory:
   ```bash
   cd QnA-Chatbot-useing-Drive-Link
   ```
3. Install the required packages:
   ```bash
   pip install -r requirements.txt
   ```

## Setup
1. Make sure to have a Google Drive account.
2. Create a service account in the Google Cloud Console and download the credentials JSON file.
3. Share the necessary documents in your Google Drive with the service account email to allow access.
4. Update your `config.json` with the path to your credentials JSON file and the IDs of the documents you want to access.

## Usage
1. Run the chatbot application:
   ```bash
   python chatbot.py
   ```
2. Open the web browser and navigate to `http://localhost:5000`.
3. Start asking questions in the provided input field.
4. The chatbot will respond based on the content available in your Google Drive documents.

## Conclusion
This QnA Chatbot provides an efficient way to retrieve information seamlessly from Google Drive, enhancing user interactions and productivity.