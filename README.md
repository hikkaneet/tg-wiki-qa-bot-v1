# tg-wiki-qa-bot-v1

## Description
This project is a Telegram bot that answers questions about the sports games in Russia in 2024 (for demo), using a knowledge base compiled from Wikipedia articles. The bot utilizes natural language processing and vector search technologies to provide accurate answers to user inquiries.

## Key Features
- Automatic data collection and processing from Wikipedia
- Text data vectorization using OpenAI embeddings
- Semantic search through the knowledge base
- Response generation using ChatGPT
- Interaction through the Telegram interface

## Technologies
- Python 3.10+
- aiogram 3.6.0 (Telegram Bot API)
- OpenAI API (embeddings and chat completion)
- pandas (data manipulation)
- mwclient and mwparserfromhell (Wikipedia parsing)
- scipy (vector calculations)

## Bot Commands
- `/start` - Start interacting with the bot
- `/help` - Information about the knowledge base (topic, number of entries, example query)

## Installation and Running
1. Install the required dependencies;
2. Set up the environment variables:
2.1. OPENAI_API_KEY,
2.2. BOT_TOKEN (Telegram);
3. Run the bot in the last cell.

## Note
The project demonstrates the application of modern natural language processing and vector search technologies to create an informational bot. The knowledge base focuses on sports events in Russia in 2024, but can be replaced by any other article.
