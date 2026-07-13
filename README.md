# AI Customer Support Automation

An AI-powered customer support automation workflow built with **n8n**, **OpenAI**, and **Gmail**.

The system automatically receives customer emails, classifies customer intent using AI, routes requests to specialized AI support agents, generates professional responses, formats them as HTML, and sends replies automatically.

This project is designed as a production-style portfolio project demonstrating modern AI workflow automation for customer support.

---

## Overview

Manual customer support is repetitive and time-consuming. This project demonstrates how AI can automate common customer support tasks while maintaining professional communication and structured workflows.

The workflow currently supports:

- AI-powered issue classification
- Intelligent workflow routing
- Specialized AI support agents
- Professional HTML email generation
- Automated Gmail replies

Future versions extend the system with Retrieval-Augmented Generation (RAG), CRM integration, ticket management, analytics, and database lookups.

---

## Features

### Version 1.0

- Gmail Trigger
- AI-generated customer support replies
- HTML email formatting
- Automatic Gmail replies
- Production-ready workflow

### Version 1.1

#### AI Issue Classification

Automatically classifies customer emails into:

- Refund
- Order Status
- Cancellation
- Damaged Product
- General Inquiry

#### Intelligent Routing

Routes customer requests using an n8n Switch node to dedicated AI support agents.

#### Specialized AI Agents

- Refund Support Specialist
- Order Status Support Specialist
- Cancellation Support Specialist
- Damaged Product Support Specialist
- General Support Specialist

#### Professional Email Generation

- HTML email formatting
- Professional customer support responses
- Consistent email signatures
- Company policy awareness
- Privacy-focused responses

---

## Workflow Architecture

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

---

## Technology Stack

- n8n
- OpenAI API
- Gmail
- HTML Email Formatting
- AI Prompt Engineering
- Workflow Automation

---

## Project Structure

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

## Documentation

Detailed documentation is available inside the `documentation/` directory.

- Version 1.0
- Version 1.1
- Architecture
- Roadmap
- Changelog

---

## Roadmap

### Version 1.2

- Knowledge Base (RAG)

### Version 1.3

- CRM Logging
- Ticket Generation
- Confidence Scoring
- Human Escalation
- Analytics Dashboard

### Version 2.0

- Mock Order Database Lookup
- AI + Database Integration
- Business Workflow Automation

---

## Skills Demonstrated

- AI Workflow Automation
- n8n Development
- Prompt Engineering
- Customer Support Automation
- Intelligent Email Routing
- Business Process Automation
- HTML Email Generation
- Workflow Architecture

---

## Author

**Reuben Mathew Tharakan**

AI & Data Science Graduate

Portfolio project focused on AI Automation, Intelligent Workflow Design, and Business Process Automation.