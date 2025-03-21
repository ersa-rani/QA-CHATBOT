# 🤖 Chatbot with Chainlit and Google Gemini API

This repository contains a simple chatbot implementation using Chainlit and Google Gemini API (via `google.generativeai` library). The chatbot can be used in two different modes: a Chainlit web-based chatbot and a terminal-based chatbot.

## ✨ Features
- 🌐 Web-based chatbot using Chainlit
- 🖥️ Terminal-based chatbot for quick interactions
- ⚡ Powered by Google Gemini API (`gemini-2.0-flash` model)
- 🔐 Uses `dotenv` for API key management

## 📌 Prerequisites
- 🐍 Python 3.x installed
- 🔑 A Google Gemini API key
- 📦 Required Python dependencies installed

## 🛠️ Installation
1. Clone the repository:
   ```sh
   git clone https://github.com/ersa-rani/chatbot-gemini.git
   cd chatbot-gemini
   ```

2. Create a virtual environment (optional but recommended):
   ```sh
   python -m venv venv
   source venv/bin/activate  # On Windows use `venv\Scripts\activate`
   ```

3. Install dependencies:
   ```sh
   pip install -r requirements.txt
   ```

4. Create a `.env` file and add your Google Gemini API key:
   ```sh
   echo "GEMINI_API_KEY=your_api_key_here" > .env
   ```

## 🚀 Running the Chainlit Chatbot
To start the web-based chatbot using Chainlit, run:
```sh
chainlit run chatbot.py
```
Then, open the provided URL in your browser to interact with the chatbot.

## 🖥️ Running the Terminal-based Chatbot
To run the terminal chatbot, execute:
```sh
python terminal_chatbot.py
```
Type your messages and press Enter to interact with the chatbot. Type `quit` to exit.

## 📂 File Overview
- `chatbot.py` 📝: Contains the Chainlit implementation of the chatbot.
- `terminal_chatbot.py` 🖥️: Implements the chatbot for command-line interaction.
- `.env` 🔑: Stores the API key (not included in the repository for security reasons).
- `requirements.txt` 📦: Lists the required Python dependencies.

## 📜 Dependencies
The project requires the following Python libraries:
```txt
chainlit
python-dotenv
google-generativeai
```

## 📄 License
This project is licensed under the MIT License.

## 👤 Author
Your Name - [GitHub Profile](https://github.com/ersa-rani)

## 🙌 Acknowledgments
- [Chainlit](https://chainlit.io/) 🚀
- [Google Gemini API](https://ai.google.dev/) 🤖

