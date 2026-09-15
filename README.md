# Tool-Using Research Agent

An AI-powered research agent that uses Gemini and external tools to answer questions with supporting evidence.

## Features

- Uses Gemini for AI reasoning
- Web search for factual research
- Calculator tool for mathematical questions
- Evidence collection
- Source selection
- Claim-level traceability checking
- Source citations
- Duplicate-search protection
- Tool failure handling
- Gemini API failure handling
- Hard step limit to prevent infinite tool calls

## Tools

### 1. Web Search

Uses DuckDuckGo to search the web and collect relevant information and sources.

### 2. Calculator

Evaluates mathematical expressions requested by the research agent.

## Architecture

User Question  
↓  
Research Agent  
↓  
Tool Selection  
↓  
Web Search / Calculator  
↓  
Evidence Store  
↓  
Source Selection  
↓  
Claim Traceability Check  
↓  
Final Answer + Sources

## Technologies

- Python
- Google Gemini API
- Google GenAI SDK
- DuckDuckGo Search
- Jupyter Notebook
- python-dotenv

## Project Structure

```text
Tool Using Research Agent/
│
├── research_agent.ipynb
├── README.md
├── requirements.txt
├── .gitignore
└── .env