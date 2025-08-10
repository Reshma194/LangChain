# 📌 LangChain Overview

LangChain is an **open-source framework** for building applications powered by **Large Language Models (LLMs)** such as GPT, LLaMA, Claude, etc.

It helps connect:

- **Models** → The AI brain (GPT, LLaMA, etc.)
- **Data Sources** → PDFs, APIs, Databases
- **Tools** → Web search, calculators, custom APIs
- **Memory** → Conversation history & context

---

## 🚀 Why LangChain?

Without LangChain, you would manually handle:
- Calling the LLM API
- Managing prompts
- Storing conversation history
- Connecting to external tools

With LangChain, you get **ready-made building blocks** so you can focus on logic, not infrastructure.

---

## 🛠 Core Components

- **Models** → Interface to LLMs (`OpenAI()`, `HuggingFaceHub()`)
- **Prompts** → Structured instructions for model output (`PromptTemplate`)
- **Chains** → Combine prompts, models, and logic
- **Memory** → Store & retrieve past interactions
- **Tools** → External functions (search, APIs, DB)
- **Agents** → LLMs that decide which tool to use & when

---
## 💡 Common Use Cases

- Chatbots with long-term memory
- Retrieval-Augmented Generation (RAG)
- AI Agents that take actions
- Document processing (summarization, extraction, classification)
