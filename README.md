# Multi-Agent AI Research System

A production-style Multi-Agent AI Research System built using LangChain, Python, and Large Language Models (LLMs).  
This project demonstrates how multiple AI agents can collaborate through an orchestrated workflow to automate research, web content extraction, report generation, and AI-driven review processes.

---

## Features

- Multi-agent workflow orchestration using LangChain
- Live web search and information retrieval
- URL scraping and content extraction
- AI-powered report generation
- Automated report review and evaluation
- Streamlit-based interactive user interface
- Modular and scalable agentic AI architecture

---

## AI Agents

### Search Agent
Retrieves relevant real-time information from the web.

### Reader Agent
Scrapes and extracts detailed content from URLs and web pages.

### Writer Agent
Generates structured research reports using LLMs.

### Critic Agent
Reviews, evaluates, and scores generated reports for quality improvement.

---

## Tech Stack

- Python
- LangChain
- Streamlit
- OpenAI / LLM APIs
- Web Scraping Tools
- REST APIs

---

## Project Architecture

```text
User Query
     ↓
Search Agent
     ↓
Reader Agent
     ↓
Writer Agent
     ↓
Critic Agent
     ↓
Final Research Report
