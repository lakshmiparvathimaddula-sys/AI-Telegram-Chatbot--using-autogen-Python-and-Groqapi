# Telegram AI Chatbot using Groq & Python

## Overview
This project is a Telegram AI Chatbot built using Python, the Telegram Bot API, and Groq's Llama 3.1 language model. The bot receives messages from Telegram users, sends them to the Groq AI model, and returns intelligent responses in real time.

## Features
- Telegram Bot Integration
- AI-Powered Conversations
- Fast Responses using Groq API
- Environment Variable Security with `.env`
- Simple and Lightweight Code Structure
- Easy Deployment and Customization

## Technologies Used
- Python 3.x
- python-telegram-bot
- OpenAI Python SDK (Groq Compatible)
- python-dotenv
- Groq API
- Telegram Bot API

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

### 3. Install Dependencies

```bash
pip install -r requirements.txt
```

## Required Libraries

```bash
pip install python-telegram-bot openai python-dotenv
```

## Environment Variables

Create a `.env` file:

```env
GROQ_API_KEY=your_groq_api_key
TELEGRAM_TOKEN=your_telegram_bot_token
```

## Running the Bot

```bash
python app.py
```

## How It Works

1. User sends a message to the Telegram bot.
2. The bot forwards the message to the Groq AI model.
3. The AI generates a response.
4. The bot sends the response back to the user.

## Security Note

Never upload your `.env` file or API keys to GitHub.

Add this to `.gitignore`:

```gitignore
.env
```

## Future Enhancements

- Voice Message Support
- Image Generation
- Multi-Language Conversations
- Database Integration
- Chat History Storage

## License

Open-source project for educational purposes.
