# 🤖 Customer Support AI Agent

Customer support teams often spend hours answering repetitive emails. This project automates that process by using AI to understand incoming customer queries, categorize them, and generate relevant responses—all through an automated **n8n** workflow.

Instead of manually checking every email, the workflow monitors a Gmail inbox, analyzes each message using an LLM through **OpenRouter**, retrieves relevant context from **Pinecone Vector Database**, and drafts a personalized reply. This enables faster, more consistent customer support while significantly reducing manual effort.

## ✨ Features

* Automatically monitors new emails received in Gmail.
* Classifies emails into categories such as Support, General Queries, and Spam.
* Retrieves relevant context using semantic search with Pinecone.
* Generates personalized, context-aware responses using an LLM.
* Sends replies automatically through Gmail.
* Built entirely as a no-code/low-code automation using n8n.

## 🛠️ Tech Stack

* n8n Cloud
* Gmail API
* OpenRouter Chat Model
* OpenAI Embeddings
* Pinecone Vector Database

## ⚙️ How It Works

1. A new email arrives in the Gmail inbox.
2. n8n automatically triggers the workflow.
3. The AI model analyzes the email and identifies its category.
4. If needed, relevant information is retrieved from Pinecone to provide additional context.
5. The LLM generates a natural, personalized response.
6. The reply is sent back to the customer automatically.

## 🎯 Why I Built This

I wanted to explore how AI agents and workflow automation can simplify everyday business operations. Customer support is a perfect use case because many queries are repetitive and time-consuming. By combining LLMs, vector search, and workflow automation, I built a system that can respond intelligently while requiring minimal human intervention.

## 🚀 Future Improvements

* Multi-language support
* Sentiment analysis for customer emails
* Integration with CRM platforms
* Human approval workflow for sensitive emails
* Analytics dashboard for support performance
