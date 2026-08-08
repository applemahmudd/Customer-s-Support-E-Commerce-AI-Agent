# Customer Support E-Commerce AI Agent 🤖📧

An AI-powered customer support automation system built with **n8n, Gmail, and Groq AI** for an e-commerce clothing business.

The agent automatically reads incoming customer emails, understands their questions, generates an appropriate response, and replies directly to the customer through Gmail.

## 🚀 Features

- 📧 Automatically detects incoming customer emails
- 🤖 AI-powered customer support using Groq
- 👕 Provides product information
- 💰 Answers product price questions
- 📏 Handles available size inquiries
- 🚚 Provides delivery information
- 💳 Supports Cash on Delivery information
- 📦 Handles customer order-related queries
- ⚡ Automatically replies to customers
- 🔄 Fully automated workflow using n8n
- 🌍 Supports customers from anywhere in Bangladesh

## 🛍️ Business Information

| Product | Price | Available Sizes |
|---|---:|---|
| Shirt | 400 BDT | L, XL, XXL |
| Pant | 300 BDT | L, XL, XXL |

### Delivery
- Delivery available all over Bangladesh
- Delivery charge: **FREE**
- Payment method: **Cash on Delivery**

## 🏗️ Workflow Architecture

```text
Customer Email
      ↓
   Gmail Trigger
      ↓
     AI Agent
      ↓
   Groq Chat Model
      ↓
Reply to Customer
