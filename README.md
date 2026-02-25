# Chatbot with Memory using OpenAI API

The project demonstrates basic concepts of AI agents such as tool calling, context management, and conversational memory. It is designed for learning purposes and to understand how to build intelligent chat systems using Python and OpenAI models.
---

###  Features

- Interactive command-line chatbot
- Memory storage for human and agent
- Tool calling using OpenAI function tools
- Context-aware responses
- Simple and beginner-friendly implementation

---

### Tech Stack

- Python
- OpenAI API
- JSON
---
### What the Code Does

The chatbot performs the following functions:

- Accepts user input through the terminal
- Sends the conversation to the OpenAI model
- Generates intelligent responses
- Uses a custom tool (core_memory_save) to store important informatio
- Maintains separate memory sections for:
    - Human
    - Agent
- Injects stored memory back into the model context
- Runs in a continuous chat loop until the user exits

---
### How to Run the Project
1️⃣ Clone the repository
``` bash
git clone https://github.com/ashhwiithac22/Editable_Memory_Chatbot.git
cd Editable_Memory_Chatbot.ipynb
```
2️⃣ Install dependencies
```
pip install openai
```
3️⃣ Set your API key (IMPORTANT)
```
OPENAI_API_KEY "your_api_key_here"
```
---
### Example
You: Hi

Bot: Hello! How can I help you today?

---
