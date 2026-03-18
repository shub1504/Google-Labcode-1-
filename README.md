# Google-Labcode-1
# 🧠 Location Intelligence AI Agent (MCP + ADK)

An intelligent AI agent built using **Google Agent Development Kit (ADK)** and powered by **Gemini**, capable of analyzing business data and real-world location context using the **Model Context Protocol (MCP)**.

---

## 🚀 Overview

This project demonstrates how to build a **production-style AI agent** that connects to real-world tools and datasets through MCP.

The agent integrates:

* 📊 Business data from BigQuery
* 🌍 Location intelligence from Google Maps

It intelligently combines both to answer complex business questions such as:

* “Where should I open a new bakery?”
* “Which areas have high demand but low competition?”

---

## 🧠 Architecture

```
User Query
   ↓
ADK Agent (Gemini-powered reasoning)
   ↓
MCP Servers (Tool Interface Layer)
   ↓
BigQuery + Google Maps
   ↓
Data Processing
   ↓
Final Intelligent Response
```
![Architecture flow](assets/screenshot.png)
---

## 🔑 Key Features

* 🔗 **MCP Integration** – Connects to external tools using standardized protocol
* 🧠 **Unified Reasoning** – Combines multiple data sources for better insights
* ☁️ **Cloud-Native** – Built and deployed using Google Cloud tools
* 📊 **Data-Driven Decisions** – Uses real datasets for analysis
* 🔐 **Secure Access** – Tools accessed via controlled MCP interfaces

---

## 🛠️ Tech Stack

* Python
* Google ADK (Agent Development Kit)
* Gemini (LLM)
* Model Context Protocol (MCP)
* BigQuery
* Google Maps API
* Google Cloud (Cloud Shell, CLI)

---

## 📂 Project Structure

```
.
├── data/                  # Dataset files
├── agent.py              # Main agent logic
├── tools.py              # Tool integrations via MCP
├── __init__.py
├── Dockerfile            # Container setup
├── requirements.txt
└── README.md
```

---

## ⚙️ How It Works

1. User sends a query to the agent
2. Agent analyzes the request using Gemini
3. Agent decides which tools to use
4. MCP connects the agent to:

   * BigQuery (data)
   * Google Maps (location insights)
5. Data is retrieved and combined
6. Agent generates a final intelligent response

---

## 🧪 Example Use Case

**Query:**

```
Where should I open a bakery?
```

**Agent Response:**

* Fetches sales and demographic data from BigQuery
* Analyzes location saturation using Google Maps
* Suggests optimal area based on demand and competition

---

## 🎯 Learning Outcomes

* Built an AI agent using ADK
* Integrated external tools using MCP
* Understood separation of reasoning and execution
* Worked with real-world data sources
* Deployed cloud-based AI systems

---

## ⚠️ Notes

* This project is part of a hands-on codelab
* Focus is on **data-to-agent integration**, not complex workflows

---

## 🙌 Acknowledgements

* Google Cloud Codelabs
* Model Context Protocol (MCP)
* Gemini & ADK ecosystem

---

## ⭐ Future Improvements

* Add more MCP tools (e.g., analytics APIs)
* Build a frontend dashboard
* Enhance reasoning with multi-agent workflows
* Deploy fully on Cloud Run

---

## 💡 Author

**Shubhangi Sharan**
BSc Computer Science (H)

---

## 📌 Final Thought

> This project showcases how modern AI systems are evolving from simple chatbots to **intelligent agents that interact with real-world systems securely and efficiently**.
