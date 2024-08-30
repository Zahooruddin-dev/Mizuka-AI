# AI Chatbot Using OpenAI API

This project is a simple AI chatbot application powered by the OpenAI API. The chatbot leverages the capabilities of OpenAI's language models to provide interactive and intelligent responses to user queries.

## Features

- **Natural Language Understanding**: The chatbot uses OpenAI's language models to understand and respond to user inputs in a natural, conversational manner.
- **Customizable Prompts**: Tailor the behavior of the chatbot by modifying prompts and settings.
- **User-Friendly Interface**: A clean and intuitive interface for interacting with the chatbot.
- **Scalable**: Designed to handle multiple users and queries efficiently.

## Getting Started

### Prerequisites

- **Node.js**: Ensure you have Node.js installed on your machine. You can download it from [nodejs.org](https://nodejs.org/).

### Installation

1. **Clone the Repository**
Navigate to the Project Directory

bash
Copy code
cd ai-chatbot
Install Dependencies

bash
Copy code
npm install
Set Up Environment Variables

Create a .env file in the root of the project directory and add your OpenAI API key:

makefile
Copy code
OPENAI_API_KEY=your-openai-api-key
Running the Application
Start the Server

bash
Copy code
npm start
Open the Application

Navigate to http://localhost:3000 in your web browser to interact with the chatbot.

Usage
Chatting with the Bot: Enter your message in the chat interface, and the bot will respond using OpenAI's language model.
Customizing Prompts: Modify the prompt settings in the code to adjust the chatbot's responses and behavior.
API Integration
This project uses the OpenAI API to power the chatbot. The API requests are made to the following endpoint:

bash
Copy code
POST https://api.openai.com/v1/engines/davinci-codex/completions


