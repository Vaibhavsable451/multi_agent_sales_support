# multi_agent_sales_support
# 🤖 Multi-Agent AI Sales & Support System

An AI-powered customer engagement platform that intelligently routes website conversations to specialized AI agents for Sales and Customer Support.

![Architecture](assets/architecture.png)

---

## 🎥 Demo

### Live Workflow Demo

https://agentfd.netlify.app/

### Demo Scenarios

✅ Product Pricing Inquiry → Routed to Sales Agent

✅ Demo Request → Routed to Sales Agent

✅ Technical Issue → Routed to Support Agent

✅ Refund Request → Routed to Support Agent

✅ Real-Time AI Responses

---

## 🚀 Overview

Most website chatbots respond the same way to every visitor.

This project introduces a Multi-Agent Architecture where a Supervisor Agent analyzes customer intent and automatically routes conversations to specialized agents.

Benefits:

* Faster customer responses
* Better lead qualification
* Reduced manual support workload
* Improved customer experience

---

## 🏗 Architecture

```text
Customer Message
        │
        ▼
┌─────────────────┐
│ Supervisor Agent │
│ Intent Routing   │
└────────┬─────────┘
         │
 ┌───────┴────────┐
 ▼                ▼

Sales Agent     Support Agent
 ▼                ▼

Response       Response
         │
         ▼

Website Chat UI
```

---

## ✨ Features

### 🧠 Supervisor Agent

* Intent Classification
* Priority Detection
* Smart Routing
* Fallback Logic

### 💰 Sales Agent

* Product Information
* Pricing Queries
* Demo Requests
* Lead Qualification

### 🛠 Support Agent

* Technical Support
* Refund Assistance
* Account Issues
* Escalation Handling

### ⚡ Platform Features

* Multi-Agent Architecture
* Real-Time Responses
* Webhook Integration
* Modular Design
* Production-Ready Workflow
* Session-Based Conversations

---

## 🛠 Tech Stack

### AI

* Groq
* Llama 3.3 70B

### Automation

* n8n

### Backend

* REST APIs
* Webhooks

### Frontend

* Custom Chat Widget

---

## 🔄 Workflow

1. User sends a message from the website.
2. Supervisor Agent analyzes intent.
3. Message is classified.
4. Request is routed to the correct AI agent.
5. Agent generates a response.
6. Response is returned instantly.

---

## 📸 Screenshots

### Workflow Architecture

![Workflow](assets/workflow.png)

### Chat Interface

![Chat UI](assets/chat-ui.png)

### Agent Routing

![Routing](assets/routing-demo.png)

---

## 📊 Example

### Sales Query

User:
"Can I get pricing details?"

Supervisor Agent:
Route → Sales

Sales Agent:
Provides plans, pricing, and next-step CTA.

---

### Support Query

User:
"My payment failed."

Supervisor Agent:
Route → Support

Support Agent:
Provides troubleshooting guidance or escalation.

---

## 🔮 Future Enhancements

* CRM Integration
* Human Handoff
* Voice AI Agents
* WhatsApp Integration
* Analytics Dashboard
* Knowledge Base (RAG)
* Multi-Language Support
* Ticketing System

---

## 💼 Business Impact

This system helps organizations:

* Reduce support costs
* Improve lead conversion
* Automate customer interactions
* Scale operations using AI agents

---

## 👨‍💻 Author

Vaibhav

MCA Graduate | AI Automation Developer

Building practical AI systems with LLMs, Automation, and Agentic AI.
