# Project 00: Hello World with LangChain

This project is a **minimal introduction to LangChain**.  
It demonstrates how to build a simple summarization pipeline using LangChain’s `PromptTemplate` and different LLM backends (OpenAI, Google Gemini, or Ollama).  

---

## ✨ Features
- Loads environment variables securely with `python-dotenv`.
- Defines a `PromptTemplate` to generate:
  1. A short summary of a person.
  2. Two interesting facts.
  3. A one-liner **not mentioned** in the provided context.
- Supports multiple LLMs (choose one by uncommenting the relevant code):
  - **Google Gemini** (`langchain-google-genai`)
  - **OpenAI GPT** (`langchain-openai`)
  - **Ollama local models** (`langchain-ollama`)

---


## 🔧 Setup

1. **Clone the repository and navigate here:**
   ```bash
   git clone https://github.com/falaque/langchain-examples.git
   cd langchain-examples/00_hello_world

2. Set up environment variables:

check .env.example file, copy it to new file .env with proper values

3. Run
  ```bash
  uv python main.py
  ```
---

Code smith example: https://smith.langchain.com/public/75a6b57d-c233-41c4-81c0-ab536291c329/r

