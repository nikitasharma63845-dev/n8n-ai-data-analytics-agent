# 🤖 AI Data Analytics Agent using n8n

An AI-powered Data Analytics Agent built using **n8n, OpenAI, Google Sheets, and Gmail**.

The agent allows users to interact with data using natural language, retrieve information from a Google Sheet, analyse the data, generate insights, and send analysis reports through Gmail.

---

## 📌 Project Overview

As part of my learning journey in **Data Analytics and AI Automation**, I built this AI Data Analytics Agent using n8n.

The goal of this project was to explore how AI agents can interact with real data sources and automate parts of the data analysis and reporting process.

Instead of manually searching through a spreadsheet, users can ask questions conversationally and allow the AI agent to retrieve and analyse the required data.

---

## 🎯 What Can the Agent Do?

The agent can:

- 💬 Accept questions through a chat interface
- 📊 Retrieve data from Google Sheets
- 🔎 Analyse spreadsheet data based on the user's question
- 🧠 Maintain conversational context using memory
- 📈 Generate data-driven insights
- 📧 Send analysis and reports through Gmail
- 🤖 Use an AI model to decide when available tools are required

---

## ⚙️ Workflow

The basic workflow is:

User
↓
Chat Trigger
↓
AI Data Analyst Agent
↓
OpenAI Chat Model
↓
Memory + Tools
↓
Google Sheets
↓
Data Analysis
↓
Insights / Response
↓
Gmail Report (when requested)

---

## 🛠️ Tools & Technologies

- n8n
- OpenAI
- Google Sheets
- Gmail
- AI Agent
- Conversational Memory

---

## 🧩 Main Components

### 1. Chat Trigger

The workflow starts when a user sends a message through the n8n chat interface.

### 2. AI Agent

The AI Agent acts as the main reasoning component of the workflow.

It determines when it needs to retrieve spreadsheet data and when it needs to send an email report.

### 3. OpenAI Chat Model

An OpenAI chat model provides the language understanding required by the AI Agent.

### 4. Simple Memory

Memory allows the agent to maintain context during a conversation.

### 5. Google Sheets Tool

The agent can retrieve rows from a Google Sheet when spreadsheet data is required for analysis.

### 6. Gmail Tool

When the user requests an analysis or report by email, the agent can generate a structured report and send it through Gmail.

---

## 💡 Example Use Cases

A user could ask questions such as:

- "Analyse the sales data."
- "What are the key insights from the dataset?"
- "Give me a summary of the data."
- "What trends can you identify?"
- "Email me the analysis."

The agent retrieves the relevant data and uses it to generate a response.

---

## 📂 Repository Contents

```text
n8n-ai-data-analytics-agent/
│
├── README.md
│
└── n8n-ai-data-analytics-agent-public.json


The JSON file contains the public-safe exported n8n workflow.

🔐 Important Note

The workflow shared in this repository has been prepared as a public-safe version.

Credentials and personal configuration details have been removed or replaced with placeholders.

To use the workflow, users will need to configure their own:

OpenAI credentials
Google Sheets credentials
Gmail credentials
Google Sheet
Email configuration

📚 Learning Reference

I built this project as part of my learning journey with n8n and AI automation.

I used an n8n AI Data Analytics Agent tutorial as a learning reference and then configured the workflow for my own project and data-analysis use case.

This project is intended as a learning and portfolio project.

🚀 What I Learned

Through this project, I learned how to:

Build an AI Agent workflow using n8n
Connect an LLM to an AI Agent
Give an AI Agent access to external tools
Connect Google Sheets to an AI workflow
Use conversational memory
Automate email reporting
Write system instructions for an AI Agent
Combine AI with data analysis and workflow automation

🔮 Future Improvements

Some areas I would like to explore next:

Add more data sources
Add data visualizations
Improve data validation
Add more advanced analytical capabilities
Connect the agent with databases
Add more robust error handling
Improve the user interface
