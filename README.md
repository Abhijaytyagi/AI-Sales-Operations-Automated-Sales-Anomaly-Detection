# AI Sales Operations – Automated Sales Anomaly Detection

This project demonstrates an **AI-powered Sales Operations assistant** that analyzes POS transaction data to proactively detect sales anomalies, explain potential causes, and recommend business actions.

Instead of relying on static dashboards or manual analysis, this system enables **conversational, on-demand sales intelligence** using AI.

---

## 🚀 Project Overview

Sales and operations teams often identify sales issues (drops, zero sales, abnormal spikes) too late.  
This project addresses that gap by:

- Analyzing store–SKU–date-level POS data
- Detecting meaningful sales anomalies
- Explaining anomalies in business-friendly language
- Recommending concrete actions for Sales Ops teams
- Allowing users to ask natural-language questions (e.g., *“Are there any anomalies?”*)

---

## 🧠 Why This Matters for AI Sales Operations

This project aligns directly with **AI Sales Operations** use cases:

- Turns raw transactional data into actionable insights
- Reduces manual reporting and analysis
- Enables faster decision-making
- Replaces static dashboards with conversational AI
- Designed with cost, scalability, and enterprise constraints in mind

---

## 📊 Data Used

The system works on POS transaction data with the following schema:

```json
{
  "store_id": "3200",
  "sku": "SKU_A",
  "date": "2025-12-04",
  "sales_qty": 8,
  "net_sales": 640
}


## 🧠 **ARCHITECTURE OVERVIEW**
POS Data (SAP / JSON)
        ↓
Data Preparation (n8n)
        ↓
AI Agent (LLM-based reasoning)
        ↓
Business Explanation + Actions
        ↓
Chat UI / API / Automation
