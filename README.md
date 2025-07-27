# 🔧 LiteLLM Tool Agent

> A minimal Python AI agent that performs real tasks by calling Python functions (aka tools).  
> Built using [LiteLLM](https://github.com/BerriAI/litellm) with full support for tool-calling, memory, and safe termination.

![MIT License](https://img.shields.io/badge/license-MIT-green)
![Python](https://img.shields.io/badge/Python-3.8%2B-blue)

---

## 🤖 What This Project Does

This script demonstrates how to build a **tool-using AI agent** that:
- 📁 Lists files in the current working directory
- 📖 Reads the contents of a selected file
- ✅ Gracefully terminates itself with a summary message

It simulates a minimal autonomous AI system using OpenAI's GPT-4o via LiteLLM's simple Python SDK.

---

## 🧠 Agent Workflow

1. The user gives a task (e.g., “Read the README”)
2. The agent first lists available files
3. It then reads the specified file
4. It ends by summarizing the task and terminating itself

---

## 🧪 How to Run

> **Recommended**: Run this in Google Colab — no local setup needed!

### ✅ Google Colab (Easy)
1. Open this repo in [Google Colab](https://colab.research.google.com/)
2. Store your API key privately:

3. 
   ```python
   from google.colab import userdata
   userdata.set("OPENAI_API_KEY", "sk-...")

---

## 🤝 Connect with Me

If you enjoyed this project or want to collaborate, feel free to connect with me:

🔗 [LinkedIn – Jonathan Dekle](https://www.linkedin.com/in/jdekle23)  
🐙 [GitHub – jdekle23](https://github.com/jdekle23)

Let’s turn data into something meaningful. 🚀
