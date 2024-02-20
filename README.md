# LLM-Based Chat-Bot Assistant with Gemini Pro, Google API, and Streamlit
This repository contains a simple chat-bot assistant powered by Google’s Gemini Pro language model. The chat-bot interacts with users in real-time through a Streamlit web interface.

real-time deployment :- [Gemeni chat-bot](https://llm-based-chat-bot-a9vxpxcn89ukfhtj3aajjn.streamlit.app/)

# Features
Gemini Pro: Utilizes Google’s Gemini Pro language model, which focuses on multimodality (text and image support).
Streamlit: Provides a user-friendly web interface for interacting with the chat-bot.
Real-time Deployment: Users can chat with the assistant in real-time.

# Prerequisites
Python 3.9+: Make sure you have Python installed on your system.
Google API Key: Obtain an API key from Google’s API Console.
google-generativeai Library: Install the library using pip install google-generativeai.

# Installation
Clone this repository:
git clone [git repo link](https://github.com/Abhishekvidhate/LLM-Based-chat-bot.git)

Install the required Python packages:
pip install -r requirements.txt

Set up your Google API key:
Create a .env file in the root directory.
Add your API key:
GOOGLE_API_KEY=your-api-key-here

# Usage
Run the Streamlit app:
streamlit run chatbot_app.py

Open your web browser and navigate to http://localhost:8501.
Start chatting with your LLM-based chat-bot assistant!
Notes
The chat-bot maintains chat history and generates responses based on user context.
Gemini Pro ensures responsible AI usage by handling unsafe queries and providing safety ratings for various categories.
Acknowledgments
This project was inspired by Google’s Gemini series and the amazing work done by the open-source community.
