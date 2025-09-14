# 🚀 RAG-Agents

A collection of ready-to-use **RAG (Retrieval-Augmented Generation) and Agent workflows** overing Gmail/Sheets integrations, local vector DB setups, multi-agent orchestrations, and various LLM tool-using patterns. Each sub-folder contains a JSON flow that can be imported into tools like **Flowise**, **n8n**, or similar orchestrators. 

Each folder is a self-contained blueprint and each workflow is made as a component which are ready to use instantly. 

---

### 📂 Project Descriptions

| Folder | Description |
|--------|------------|
| **Claude MCP Server – Gmail Sheets & Vector DB** | Sets up a Claude MCP server that listens to Gmail events and writes or reads data from Google Sheets while syncing with a Vector DB. Enables automated email analysis and context-aware document retrieval inside one flow. |
| **Contexual Retrieval RAG Flow using GrokCloud** | Demonstrates contextual chunking and retrieval powered by GrokCloud. It enriches RAG with dynamic context windows to improve precision on long or complex documents. |
| **Custom ChatGPT Agent – Gmail & Calendar & Sheets** | A multi-service ChatGPT agent that connects to Gmail, Google Calendar, and Sheets through webhooks. Provides unified scheduling, email summarization, and spreadsheet updates from a single conversational interface. |
| **Flowise to n8n via HTTP Request (CURL)** | Shows how to trigger n8n automations directly from Flowise using HTTP requests or cURL. Includes two sample flows: one for generic webhook triggers and another for cURL-based calls. |
| **Leads RAG Agent** | Captures and enriches sales leads, storing them in Pinecone for vector-based semantic search. Ideal for quickly retrieving or ranking prospects by similarity and relevance. |
| **Local RAG Agent – Ollama & PgVector – PG DB Manager** | Runs a fully local RAG pipeline with Ollama as the LLM and Postgres/pgvector as the vector database. Includes a simple database-manager interface for monitoring and updates. |
| **Local RAG Agent – Ollama & Qdrant** | Self-hosted agent that pairs Ollama with a Qdrant vector DB. Provides private semantic search without relying on cloud services. |
| **Local RAG Agent – Ollama & Supabase** | Combines Ollama inference with Supabase’s vector storage and authentication. Supports secure, low-latency RAG for internal or enterprise deployments. |
| **Multi Agent RAG – Flowise** | Coordinates multiple specialized agents in Flowise for internet search, writing assistance, and vector-database retrieval. Demonstrates collaborative agent orchestration for complex tasks. |
| **Multi Agent RAG – Serp API** | Uses the SERP API to allow multiple agents to perform real-time web searches. Integrates with n8n for downstream automation and data enrichment. |
| **Multi MCP Server – Zapier & Gmail Sheets** | A multi-service MCP server that bridges Zapier workflows with Gmail and Google Sheets. Automates email handling and sheet updates across diverse apps. |
| **RAG GCP & Pinecone** | Deploys a RAG pipeline on Google Cloud Platform while storing embeddings in Pinecone. Shows how to leverage scalable cloud infrastructure for high-volume retrieval. |
| **RAG Q&A – Web Chatflow** | Web-based question-answering interface backed by a RAG pipeline. Lets users chat with their documents through a browser with instant semantic search. |
| **RAG Q&A – Web Chatflow Ollama** | Same as the Web Chatflow project but powered entirely by a local Ollama model for privacy-first Q&A without external LLM calls. |
| **RAG Tool Agent – calculator + Brave + Writefile + OpenRouter** | An advanced tool-using agent that can browse with Brave, perform calculations, write files, and query OpenRouter. Useful for research or automated reporting workflows. |
| **Web Scraping Agent** | Crawls websites using robots.txt and sitemaps to collect data for later analysis or RAG ingestion. Automates large-scale content acquisition. |
| **Web Scraping RAG Multi Agent** | A multi-agent system that scrapes web data and immediately feeds it into a RAG pipeline and saves it in vector DB. Enables near real-time knowledge vector-DB updates for live data querying. |

---

### 🚀 Quick Start Guide

```
1. Open Flowise or n8n.
2. Click **Import Flow**.
3. Select any `.json` file from this repo.
4. Provide the required API keys (OpenAI, Pinecone, etc.) in the environment variables.
```





