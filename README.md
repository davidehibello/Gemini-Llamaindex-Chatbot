
# 🤖 Gemini LlamaIndex Chatbot

An interactive AI chatbot built using **Google’s Gemini API** and **LlamaIndex**, designed for real-time, context-aware conversations.  
This project demonstrates how to integrate large language models (LLMs) into a simple yet scalable Python-based chatbot pipeline.

---

## 🚀 Features
- 💬 Real-time conversational interface using Gemini’s LLM.
- 🧠 Context retention powered by LlamaIndex `ChatMessage` structures.
- 🔐 Secure API key management through environment variables.
- ⚙️ Modular design — easy to extend with retrieval, embeddings, or external data sources.
- 🪶 Lightweight setup ideal for experimentation or integration with larger GenAI systems.

---

## 🛠️ Tech Stack
- **Language:** Python  
- **Frameworks/Libraries:** LlamaIndex, Gemini API  
- **Tools:** Google Colab, Environment Variables, PyPI  

---

## 📦 Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/gemini-llamaindex-chatbot.git
   cd gemini-llamaindex-chatbot

2. Install dependencies:
   ```bash
   pip install llama-index llama-index-llms-gemini

3. Set your Gemini API key:
   ```bash
   import os
   os.environ["GEMINI_API_KEY"] = "YOUR_API_KEY"

## 💻 Usage

Run the chatbot:
   ```bash
   python chatbot.py
   ```
 Example interaction:
 ```bash
 Simple Gemini Chatbot 
Type 'exit' to end the conversation
--------------------------------------------------

You: Hi, how are you?
Chatbot: I'm doing great! How can I assist you today?
 ```
## 🧩 How It Works

Initializes Gemini via the LlamaIndex Gemini class.

Maintains a conversation history using ChatMessage.

Sends user messages to the Gemini LLM and displays contextual responses.

Gracefully handles errors such as invalid API keys or connection issues.

## 🧠 Future Improvements

Add retrieval-augmented generation (RAG) for document-based conversations.

Integrate with Streamlit or Gradio for a graphical chat interface.

Expand memory handling for long-term chat context.
