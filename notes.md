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
## 💡 Common Use Cases

- Chatbots with long-term memory
- Retrieval-Augmented Generation (RAG)
- AI Agents that take actions
- Document processing (summarization, extraction, classification)
---
# 📌 LangChain Components

LangChain is built from **modular components** that help in building powerful AI applications using Large Language Models (LLMs).

---

## 1. Models
**Definition:** The brain of the application — responsible for generating responses.  
**Examples:** `OpenAI()`, `ChatOpenAI()`, `HuggingFaceHub()`, `Ollama()`  
**Types:**
- **LLM** → Single text input/output
- **ChatModel** → Structured conversation format (system, user, assistant roles)

---

## 2. Prompts
**Definition:** Instructions given to the model to guide its output.  
**Purpose:** Control the style, tone, and content of model responses.  
**Examples:**
- `PromptTemplate` → Dynamic text prompts
- `ChatPromptTemplate` → Chat-based prompts

---

## 3. Chains
**Definition:** A sequence of steps combining prompts, models, and logic.  
**Purpose:** Automate multi-step tasks.  
**Examples:**
- `LLMChain` → LLM + Prompt
- `SequentialChain` → Multiple chains in order

---

## 4. Memory
**Definition:** Stores and retrieves conversation history or context for the model.  
**Purpose:** Enables continuity in multi-turn conversations.  
**Types:**
- `ConversationBufferMemory` → Stores all messages
- `ConversationBufferWindowMemory` → Stores recent N messages
- `VectorStoreRetrieverMemory` → Embedding-based retrieval

---

## 5. Tools
**Definition:** External functions or APIs that the model can call.  
**Purpose:** Extend LLM capabilities beyond text generation.  
**Examples:** Web search, API calls, calculators, database queries.

---

## 6. Agents
**Definition:** LLMs that **decide which actions to take** and use tools accordingly.  
**Purpose:** Give LLMs decision-making power for dynamic workflows.

---

## 7. Indexes / Retrievers
**Definition:** Structures for storing and retrieving external data efficiently.  
**Purpose:** Support Retrieval-Augmented Generation (RAG).  
**Examples:** `FAISS`, `Pinecone`, `Chroma`

