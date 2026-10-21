# Basic Chatbot with LangGraph

A simple chatbot built using LangGraph's StateGraph API.

## What You'll Learn

1. **Basic Chatbot** — Build a minimal chatbot using LangGraph's graph-based architecture
2. **Chatbot with Tools** — Enhance the chatbot with external tools (web search, custom functions)

## Key Concepts

- **StateGraph** — Core LangGraph component for building graph-based workflows
- **Nodes** — Functions that process state
- **Edges** — Connections between nodes that define the flow
- **Tools** — External capabilities (search, computation) bound to the LLM

## Setup

```bash
pip install -r requirements.txt
cp .env.example .env   # Add your API keys
python chatbot.py
```
