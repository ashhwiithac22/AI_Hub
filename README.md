# 🤖 AI Agent & Local LLM 

This repository demonstrates how to:

* Run **LLMs locally using Ollama**
* Build **AI agents using LangChain**
* Use **OpenAI models**
* Implement **tool calling and reasoning**
* Create an **editable memory chatbot**


# 📌 Project Modules

This repo currently contains:

* 🦙 Local LLM with Ollama
* 🔗 LangChain AI Agent
* 🧠 Editable Memory Chatbot
* 🧭 Mermaid diagram generation


# 🚀 Features

* Interactive AI agent
* Local LLM execution via Ollama
* Tool calling (Math, Wikipedia, Python REPL)
* Context-aware responses
* Custom tool support (date tool)
* Debug mode for agent reasoning
* Mermaid diagram generation
* Beginner-friendly implementation


# 🛠 Tech Stack

* Python
* LangChain
* OpenAI API
* Ollama
* dotenv
* JSON
* Mermaid

---

# 🦙 Part 1 — Local LLM with Ollama

## 📖 Overview

This section demonstrates how to run a **Large Language Model locally** using Ollama and interact with hosted models like **minimax-m2.5**.

It generates:

* Machine Learning overview
* Types of ML
* Common algorithms
* Real-world applications
* Visual Mermaid diagrams


## 🖥️ Start Ollama

```bash
ollama
```

## 📥 Pull a Model (example)

```bash
ollama pull minimax-m2.5
```


## ▶️ Run the Model

```bash
ollama run minimax-m2.5
```

You can now interact with the model directly from the terminal.

---

# 🔗 Part 2 — LangChain AI Agent

## 🧠 Concepts Covered

* Agent initialization
* Tool usage
* ReAct reasoning
* Python execution via agent
* External knowledge retrieval
* Custom tool creation


## ⚙️ Setup 

### 1️⃣ Clone the Repository

```bash
git clone https://github.com/ashhwiithac22/Editable_Memory_Chatbot.git
cd Editable_Memory_Chatbot
```


### 2️⃣ Install Dependencies

```bash
pip install openai langchain langchain-openai langchain-experimental python-dotenv wikipedia numexpr
```



### 3️⃣ Set Your API Key 

 set in code:

```python
import os
os.environ["OPENAI_API_KEY"] = "your_api_key_here"
```


# 🔗 How the Langchain Agent  Works
- Receives user query → The agent takes the user's question or task as input.
- Decides which tool to use → Using ReAct reasoning, the agent determines whether to use math, Wikipedia, Python, or a custom tool.
- Calls the selected tool → The agent executes the tool and gathers the result.
- Processes the result with the LLM → The LLM interprets the tool output and prepares the final answer.
- Returns the final response → The user receives a context-aware, intelligent reply.

--- 
# 🧠 Part 3 - Editable Memory Chatbot

This project also explores:

* Persistent memory concepts
* Context injection
* Tool-based memory saving
* Human vs Agent memory separation

📌 Purpose: To understand how **long-term conversational agents** work.


# 🧠 How the Editable Memory Chatbot Works

- Captures user conversation → The chatbot listens to user inputs during the chat loop.
- Stores important information → Key details are saved using a memory tool (e.g., core_memory_save).
- Maintains separate memory sections → Memory is organized for Human and Agent contexts.
- Injects memory into future prompts → Stored memory is added back into the model context for better continuity.
- Generates context-aware replies → The chatbot responds using both the current input and past memory.

--- 
