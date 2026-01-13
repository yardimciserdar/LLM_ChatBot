# Google Gemini LLM ChatBot

A simple yet powerful chatbot implementation interacting with Google's Gemini models. This project demonstrates how to use the Google Gemini API directly and integrates with LangChain for more advanced capabilities.

## 🚀 Features

- **Google Gemini API Integration:** Direct interaction with models like `gemini-2.5-flash`, `gemini-pro`, etc.
- **Secure API Key Handling:** Utilizes Google Colab's `userdata` for secure key management (or manual input).
- **Model Discovery:** Utility to list and filter available models that support content generation.
- **Interactive Chat Loop:** A console-based chat interface with conversation history memory.
- **LangChain Support:** Examples showing how to use `langchain-google-genai` for building LLM applications.

## 📋 Prerequisites

- **Python 3.10+**
- **Google API Key:** Get your key from [Google AI Studio](https://aistudio.google.com/).

## 🛠️ Installation

Install the required Python packages:

```bash
pip install google-generativeai langchain-google-genai langchain-community
```

## 📖 Usage

### 1. API Key Setup
The notebook is designed to run primarily in Google Colab, where you can securely store your API key in the "Secrets" (🔑) tab with the name `GOOGLE_API_KEY`.

If running locally or in a different environment, ensure your API key is available, for example by setting an environment variable:

```bash
export GOOGLE_API_KEY="your_api_key_here"
```

### 2. Running the ChatBot
Open `LLM ChatBot.ipynb` in Jupyter Notebook or Google Colab and run the cells sequentially.

- **Initialization:** Import libraries and configure the API key.
- **List Models:** Run the model listing cell to see which Gemini versions are available to you.
- **Start Chat:** Execute the main loop cell to start chatting. Type `exit`, `quit`, or `çıkış` to end the session.

### 3. LangChain Example
The notebook also contains a section for LangChain integration:
1. Initialize `GoogleGenerativeAI` with your specific model.
2. Use `.invoke()` to send simple prompts.
3. Build more complex chains if needed.

## 🤝 Contributing
Feel free to open issues or submit pull requests if you have suggestions for improvements!
