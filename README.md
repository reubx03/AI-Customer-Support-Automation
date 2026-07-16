# AI Customer Support Automation

An AI-powered customer support automation workflow built with **n8n**, **OpenAI**, and **Gmail**.

The system automatically receives customer emails, classifies customer intent using AI, routes requests to specialized AI support agents, retrieves relevant company knowledge using Retrieval-Augmented Generation (RAG), generates professional responses, formats them as HTML, and sends replies automatically.

This project is designed as a production-style portfolio project demonstrating modern AI workflow automation for customer support.

---

## Overview

Manual customer support is repetitive and time-consuming. This project demonstrates how AI can automate common customer support tasks while maintaining professional communication, intelligent routing, and accurate knowledge retrieval.

The workflow currently supports:

- AI-powered issue classification
- Intelligent workflow routing
- Specialized AI support agents
- Retrieval-Augmented Generation (RAG)
- Company Knowledge Base search
- OpenAI Embeddings
- Simple Vector Store
- AI Agent with conversation memory
- Professional HTML email generation
- Automated Gmail replies

Future versions extend the system with CRM integration, ticket management, analytics, human escalation, and database lookups.

---

# Features

## Version 1.0

- Gmail Trigger
- AI-generated customer support replies
- HTML email formatting
- Automatic Gmail replies
- Production-ready workflow

---

## Version 1.1

### AI Issue Classification

Automatically classifies customer emails into:

- Refund
- Order Status
- Cancellation
- Damaged Product
- General Inquiry

### Intelligent Routing

Routes customer requests using an n8n Switch node to dedicated AI support agents.

### Specialized AI Support Agents

- Refund Support Specialist
- Order Status Support Specialist
- Cancellation Support Specialist
- Damaged Product Support Specialist
- General Support Specialist

### Professional Email Generation

- HTML email formatting
- Professional customer support responses
- Consistent email signatures
- Company policy awareness
- Privacy-focused responses

---

## Version 1.2

### Retrieval-Augmented Generation (RAG)

Implemented a complete RAG pipeline allowing the AI to retrieve company knowledge before generating responses.

### Knowledge Base

- Company Knowledge Base
- GitHub Knowledge Loader
- Automatic Markdown Download
- Centralized Company Policies

### Document Processing

- Default Data Loader
- Recursive Character Text Splitter
- Chunk-based document processing

### AI Knowledge Retrieval

- OpenAI Embeddings
- Simple Vector Store
- AI Agent
- Vector Store Question Answer Tool
- Conversation Memory

### Benefits

- Reduces AI hallucinations
- Answers based on company policies
- Easily updateable knowledge base
- Improved response accuracy

---

# Workflow Architecture

```text
Customer Email
        │
        ▼
 Gmail Trigger
        │
        ▼
 AI Issue Classifier
        │
        ▼
 Switch Routing
        │
 ┌──────────────┬───────────────┬───────────────┬──────────────┐
 │              │               │               │              │
Refund     Order Status   Cancellation   Damaged Product   General Inquiry
 │              │               │               │              │
 └──────────────┴───────────────┴───────────────┴──────────────┘
                        │
                        ▼
              HTML Email Formatter
                        │
                        ▼
                Gmail Send Reply
```

> **Version 1.2** extends the workflow with a Retrieval-Augmented Generation (RAG) pipeline that retrieves relevant company policies from a knowledge base before generating customer responses.

---

# Technology Stack

- n8n
- OpenAI API
- GPT-5 Mini
- OpenAI Embeddings
- Gmail API
- HTML Email Formatting
- AI Prompt Engineering
- Retrieval-Augmented Generation (RAG)
- Simple Vector Store
- AI Agent
- Workflow Automation

---

# Project Structure

```text
AI-Customer-Support-Automation/

assets/
documentation/
knowledge-base/
prompts/
sample-emails/
workflow/

README.md
LICENSE
.gitignore
```

---

# Documentation

Detailed documentation is available inside the `documentation/` directory.

- Version 1.0 – AI Email Automation
- Version 1.1 – AI Classification & Intelligent Routing
- Version 1.2 – Retrieval-Augmented Generation (RAG)

---

# Roadmap

## ✅ Version 1.0

- AI Email Automation

## ✅ Version 1.1

- AI Issue Classification
- Intelligent Routing
- Specialized AI Support Agents

## ✅ Version 1.2

- Knowledge Base (RAG)
- OpenAI Embeddings
- Simple Vector Store
- AI Agent
- Company Policy Search
- Conversation Memory

## 🚀 Version 1.3

- CRM Logging
- Ticket Generation
- Confidence Scoring
- Human Escalation
- Analytics Dashboard

## 🚀 Version 2.0

- Mock Order Database Lookup
- AI + Database Integration
- Business Workflow Automation

---

# Skills Demonstrated

- AI Workflow Automation
- n8n Development
- Prompt Engineering
- Customer Support Automation
- Intelligent Email Routing
- Retrieval-Augmented Generation (RAG)
- Vector Databases
- Semantic Search
- AI Agents
- Business Process Automation
- HTML Email Generation
- Workflow Architecture

---

# Author

**Reuben Mathew Tharakan**

AI & Data Science Graduate

Portfolio project focused on AI Automation, Intelligent Workflow Design, Retrieval-Augmented Generation (RAG), AI Agents, and Business Process Automation.