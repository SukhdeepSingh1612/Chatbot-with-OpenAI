# 🧠 Q&A Chatbot with Ollama and Langchain

This is a lightweight, local chatbot powered by [Ollama](https://ollama.com) and [Langchain](https://www.langchain.com/). It uses the `gemma:2b` model and tracks interactions using LangSmith.

---

## 🚀 Features

- Streamlit UI for interactive Q&A  
- Powered by Ollama's local LLMs (`gemma:2b`)  
- Langchain for prompt engineering and chaining  
- LangSmith for project tracking  

---

## 🔧 Setup Instructions

### 1. Clone the Repository

```bash
git clone https://github.com/yourusername/ollama-chatbot.git
cd ollama-chatbot
```

### 2. Install Python Requirements

We recommend using a virtual environment:

```bash
pip install -r requirements.txt
```

### 3. Install and Run Ollama

Download and install Ollama from [here](https://ollama.com/download).  
Then pull and run the `gemma:2b` model:

```bash
ollama pull gemma:2b
ollama run gemma:2b
```

This must be running in the background for the chatbot to function.

### 4. 🔐 Environment Variables

Create a `.env` file in the root directory and add your Langchain API key to enable LangSmith tracking:

```env
LANGCHAIN_API_KEY=your_langchain_api_key_here
```

### 5. 💡 Run the App

```bash
streamlit run streamlit_app.py
```

Open the URL displayed in the terminal to interact with the chatbot.
