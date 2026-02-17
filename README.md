# PayPal Agent Toolkit

A comprehensive, multi-language toolkit that enables popular agent frameworks to integrate with PayPal APIs through function calling. Includes support for **Python** and **TypeScript**, built on top of PayPal APIs and PayPal SDKs.

## 🚀 Overview

The PayPal Agent Toolkit makes it seamless to integrate PayPal's payment capabilities into AI agent frameworks including:

- **OpenAI** (Agent SDK, Assistants API)
- **LangChain**
- **Vercel's AI SDK**
- **CrewAI**
- **Amazon Bedrock**
- **Model Context Protocol (MCP)** for Claude Desktop, Cline, Cursor, and GitHub Copilot

Manage PayPal transactions through natural language with AI agents—create invoices, process payments, manage disputes, track shipments, and gain business insights.

## 📦 Languages Supported

### Python
- **Package**: `paypal-agent-toolkit`
- **Python Version**: 3.11+
- **Frameworks**: OpenAI SDK, LangChain, CrewAI, Amazon Bedrock
- **Documentation**: See [python/README.md](./python/README.md)

### TypeScript
- **Package**: `@paypal/agent-toolkit`
- **Node Version**: 18+
- **Frameworks**: Vercel AI SDK, OpenAI, LangChain, Amazon Bedrock, MCP
- **Documentation**: See [typescript/README.md](./typescript/README.md)

## 🛠️ Available Tools

The toolkit provides comprehensive tools for managing PayPal operations:

### 💰 **Invoices**
- Create, list, retrieve, and send invoices
- Send invoice reminders
- Cancel invoices and generate QR codes

### 💳 **Payments**
- Create orders and retrieve order details
- Process payments and refunds
- Full payment lifecycle management

### ⚖️ **Dispute Management**
- List and retrieve disputes
- Accept dispute claims
- Comprehensive dispute handling

### 📦 **Shipment Tracking**
- Create and manage shipment tracking
- Update tracking information in real-time

### 📊 **Catalog Management**
- Create products and manage your catalog
- List and retrieve product details

### 📅 **Subscription Management**
- Create and manage subscription plans
- Handle subscriptions with ease
- Update and cancel subscriptions

### 📈 **Reporting & Insights**
- List transactions with filtering
- Retrieve merchant analytics and KPIs

## 🚀 Quick Start

### Python Installation
```bash
pip install paypal-agent-toolkit
