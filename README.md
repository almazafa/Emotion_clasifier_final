# Emotion Text Classification using BERT pre-trained model
This repository contains the code for text classification using pre-trained BERT model.

### Description
This project includes a Telegram bot designed to interact with users by processing text, voice, and photo messages. It utilizes Natural Language Processing (NLP) and facial emotion recognition technologies to analyze and respond to user inputs. The bot is capable of handling various commands and provides emotional analysis of the messages.



### Features
Text Analysis: Analyzes text messages using BERT for sentiment analysis.
Voice Handling: Processes voice messages and converts them to text for analysis.
Photo Handling: Analyzes photos, especially faces, to detect emotions.
Command Response: Responds to specific user commands like /start, /help, etc.

### Technologies Used
Python 3.8+

Telegram Bot API

Transformers (BERT model)

FER (Facial Emotion Recognition)

Telebot


### Setup
To run this project, you will need to install several Python libraries and set up environment variables.


### Prerequisites
1.Python 3.8 or higher

2.Pip


### Installation
To install the dependencies run:
```buildoutcfg
pip install -r requirements.txt
```

### Environment Variables

To run this project, you will need to add the following environment variables to your .env file:

TOKEN_TELEGRAM - Your Telegram Bot Token

TELEGRAM_API_URL - Base URL for the Telegram API


### Usage

To start the bot, run the following command:

open telegram application 


### Project Structure

bot.py: Main script for the Telegram bot.

emotion_analysis.py: Module for handling text and photo emotion analysis.

voice_handler.py: Module for processing voice messages.

utils.py: Utility functions used across the project.

### How to Contribute

Fork the project

Create your feature branch (git checkout -b feature/AmazingFeature)

Commit your changes (git commit -m 'Add some AmazingFeature')

Push to the branch (git push origin feature/AmazingFeature)

Open a Pull Request

