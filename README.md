# 💬 OpenAI-Powered Q&A Chatbot

This is a simple, local chatbot application that leverages OpenAI's language models through user-provided API keys. It features a clean Streamlit interface where users can enter their OpenAI API key and select the desired model (e.g., `gpt-3.5-turbo`, `gpt-4`).

---

## 🚀 Features

- Streamlit-based interactive chat UI  
- User inputs their own OpenAI API key  
- Supports model selection (e.g., `gpt-3.5-turbo`, `gpt-4`)  
- Lightweight and easy to set up  

---

## 🔧 Setup Instructions

### 1. Clone the Repository

```bash
git clone https://github.com/yourusername/openai-chatbot.git
cd openai-chatbot
```

### 2. Install Python Requirements

We recommend using a virtual environment:

```bash
pip install -r requirements.txt
```

### 3. 🛠️ Configuration

The user will be prompted to enter their OpenAI API key directly in the app interface.
Create a `.env` file in the root directory and add your Langchain API key to enable LangSmith tracking:

```env
LANGCHAIN_API_KEY=your_langchain_api_key_here
```



### 4. 💡 Run the App

```bash
streamlit run streamlit_app.py
```

Open the URL displayed in the terminal to start chatting.  
You'll be prompted to enter your OpenAI API key and choose the model you want to use.

---

## 📌 Notes

- Your API key is not stored anywhere; it is only used in the current session.  
- Ensure you have a valid [OpenAI API key](https://platform.openai.com/account/api-keys) and access to the selected model.
