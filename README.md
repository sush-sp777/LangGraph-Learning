# LangGraph Learning – Chatbots & Tool-Based Agents

This repository contains my hands-on learning and implementations using **LangGraph**, the modern framework for building stateful, multi-step AI agents.  
The focus is on understanding **chatbots, tool calling, and agent workflows** using updated LangChain + LangGraph patterns.

---

## 📌 What this repository covers

- Basics of LangGraph
- State management using `StateGraph`
- Message handling with `add_messages`
- Building chatbots using LangGraph
- Tool-based agents (ArXiv tool integration)
- Conditional tool execution using `tools_condition`
- Streaming responses from agents

---

## 🤖 1. Basic LangGraph Chatbot

**File:** `langgraph_chatbot.ipynb`

### Features:
- Uses `StateGraph` for managing conversation state
- Maintains chat history using `add_messages`
- Simple START → chatbot → END workflow
- Streaming responses from the LLM

### Concepts learned:
- LangGraph nodes & edges
- State definition using `TypedDict`
- Difference between LangChain chains and LangGraph graphs

---

## 🔧 2. LangGraph Chatbot with ArXiv Tool

**File:** `02_langgraph_chatbot_with_tool.ipynb`

### Features:
- Tool-augmented chatbot
- Uses **ArXiv** as an external research paper tool
- Conditional tool execution using `tools_condition`
- Prevents unnecessary tool usage via system instructions

### Tools Used:
- `ArxivAPIWrapper`
- `ArxivQueryRun`

### Concepts learned:
- Tool binding with LLMs
- ToolNode in LangGraph
- Conditional edges in graphs
- How LLM decides when to use tools

---

## 🧠 Tech Stack

- **Python**
- **LangGraph**
- **LangChain**
- **Groq LLM (LLaMA 3.1)**
- **ArXiv API**

---

