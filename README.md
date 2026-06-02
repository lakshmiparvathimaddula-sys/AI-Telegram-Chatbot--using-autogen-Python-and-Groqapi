# Telegram AI Chatbot using Groq & Python

## Overview

This project is a Telegram AI Chatbot built using Python, the Telegram Bot API, and Groq's Llama 3.1 language model. The bot receives messages from Telegram users, sends them to the Groq AI model, and returns intelligent responses in real time.

## Features

* Telegram Bot Integration
* AI-Powered Conversations
* Fast Responses using Groq API
* Environment Variable Security with `.env`
* Simple and Lightweight Code Structure
* Easy Deployment and Customization

## Technologies Used

* Python 3.x
* python-telegram-bot
* OpenAI Python SDK (Groq Compatible)
* python-dotenv
* Groq API
* Telegram Bot API

## Project Structure

```text
project/
│
├── app.py
├── .env
├── requirements.txt
└── README.md
```

## Installation

### 1. Clone the Repository

```bash
git clone https://github.com/your-username/telegram-ai-chatbot.git
cd telegram-ai-chatbot
```

### 2. Create a Virtual Environment

```bash
python -m venv venv
```

Activate the virtual environment:

**Windows**

```bash
venv\Scripts\activate
```

**Linux/Mac**

```bash
source venv/bin/activate
```

### 3. Install Dependencies

```bash
pip install -r requirements.txt
```

## Required Libraries

Install the following libraries:

```bash
pip install python-telegram-bot openai python-dotenv
```

Or use a requirements file:

```txt
python-telegram-bot
openai
python-dotenv
```

## Environment Variables

Create a `.env` file in the project root directory.

```env
GROQ_API_KEY=your_groq_api_key
TELEGRAM_TOKEN=your_telegram_bot_token
```

## Running the Bot

Start the chatbot using:

```bash
python app.py
```

If everything is configured correctly, the terminal will display:

```text
Bot Running...
```

## How It Works

1. User sends a message to the Telegram bot.
2. The bot receives the message using the Telegram API.
3. The message is forwarded to the Groq Llama model.
4. The AI generates a response.
5. The bot sends the response back to the user.

## Sample Conversation

**User:**

```
What is Artificial Intelligence?
```

**Bot:**

```
Artificial Intelligence (AI) is the simulation of human intelligence in machines that can learn, reason, and solve problems.
```

## Security Note

Never upload your `.env` file or API keys to GitHub.

Add `.env` to your `.gitignore` file:

```gitignore
.env
```

## Future Enhancements

* Voice Message Support
* Image Generation
* Multi-Language Conversations
* Chat History Storage
* Database Integration
* User Authentication
* Web Dashboard

## Author

Developed using Python, Telegram Bot API, and Groq AI.

## License

This project is open-source and available for educational and personal use.
