# Splunk MCP Server (Developer Extension)

## Introduction
The Model Context Protocol (MCP) server provides AI assistants with a secure interface to develop, search, analyze, and validate Splunk queries using built-in safety guardrails.  
While the standard Splunk MCP server primarily supports **user-level development**, this project extends MCP capabilities for **developer-level workflows**.

Our goal is to build an **AI development bot** that:
- Recognizes important and distinctive patterns across Splunk **Technology Add-ons (TA)**, **Supporting Add-ons (SA)**, **Domain Add-ons (DA)**, and **App development**  
- Enforces **good programming practices**, guiding learners to adopt and reinforce effective patterns throughout their Splunk development journey  
- Bridges the gap between **user-focused query execution** and **developer-focused design patterns**, helping teams scale their Splunk solutions with consistency, safety, and maintainability  

---

## Why This Matters
- **User-level focus isn’t enough**: The existing MCP server validates queries and protects environments, but it doesn’t teach or enforce development best practices.  
- **Developer extension**: By embedding programming guidance, this project empowers new Splunk developers to learn faster and avoid common pitfalls.  
- **Pattern recognition**: The AI bot highlights reusable structures across TA, SA, DA, and Apps, ensuring developers follow proven approaches.  

---

## Key Features
- 🔒 **Secure Query Validation** – Built-in guardrails to prevent destructive or resource-intensive queries  
- 🧠 **Developer-Focused AI Bot** – Pattern recognition across TA, SA, DA, and Apps  
- 📚 **Programming Guidance** – Enforces good habits and best practices for learners  
- ⚡ **Scalable Workflows** – Bridges user-level query execution with developer-level design  

---

## Quick Start
### Python Implementation
```bash
cd python
cp .env.example .env   # Edit .env with your Splunk credentials
pip install -e .
python server.py
