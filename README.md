# lite-llm-tool-agent
A minimal Python agent that calls its own tools (list, read, terminate) using LiteLLM, ready to run locally or in Google Colab.

# Tool Agent Demo with LiteLLM
This is a minimal Python AI agent that interacts with its environment by calling tools (functions). It uses [LiteLLM](https://github.com/BerriAI/litellm) to interface with OpenAI models like `gpt-4o`.

## 🔧 Features
- 📁 Lists files in the directory
- 📖 Reads contents of a file
- ✅ Terminates with a final message

## 🚀 How to Run
> This project runs in both **local environments** and **Google Colab**.

### 🚀 Run in Google Colab (Recommended)
1. Click the “Open in Colab” badge (or [open the notebook directly](#) if you’ve cloned the repo).
2. Store your OpenAI key securely in Colab by running:
   ```python
   from google.colab import userdata
   userdata.set('OPENAI_API_KEY', 'sk-...')

