# 🤖 AI Chat Agent with Tools – n8n Workflow

This is an intelligent AI Agent built using [n8n](https://n8n.io), designed to respond to chat messages with enhanced capabilities. It leverages OpenAI's GPT model, includes memory handling, and integrates useful tools like a calculator and web search via SerpAPI.

---

## 🚀 Features

- ✅ Responds to incoming chat messages
- 🧠 Remembers previous interactions using **Simple Memory**
- 🤖 Uses **OpenAI Chat (GPT)** for responses
- 🧮 Can solve math problems with a **Calculator tool**
- 🔍 Can answer current affairs & factual questions via **SerpAPI (Google Search)**

---

## 🛠 Tech Stack

- [n8n](https://n8n.io) - Workflow automation
- [OpenAI](https://openai.com/) - Chat model (GPT)
- [SerpAPI](https://serpapi.com/) - Search engine tool
- Calculator (via LangChain Tools)
- Simple memory for conversational context

---

## 🧩 Workflow Overview

1. **Trigger** – Starts when a chat message is received
2. **AI Agent (Tools Agent)** – Handles the conversation
   - Connects to:
     - 💬 OpenAI Chat Model
     - 🧠 Memory
     - ➕ Tools:
       - Calculator
       - SerpAPI
3. Responds based on message type:
   - Factual queries ➜ SerpAPI
   - Math ➜ Calculator
   - General chat ➜ OpenAI

---

## ⚙️ Setup Instructions

### 1. Clone the repo

```bash
git clone https://github.com/your-username/my-n8n-agent.git
cd my-n8n-agent
