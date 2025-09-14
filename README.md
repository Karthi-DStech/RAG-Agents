# 🚀 RAG-Agents

A collection of ready-to-use **RAG (Retrieval-Augmented Generation) and Agent workflows** overing Gmail/Sheets integrations, local vector DB setups, multi-agent orchestrations, and various LLM tool-using patterns. Each sub-folder contains a JSON flow that can be imported into tools like **Flowise**, **n8n**, or similar orchestrators. 

Each folder is a self-contained blueprint and each workflow is made as a component which are ready to use instantly. 

---

### 📂 Project Descriptions

**Claude MCP Server – Gmail Sheets & Vector DB**  
- Triggers a Claude MCP server to pull Gmail and Google Sheets data.  
- Parses emails and sheet entries, transforms them into vector embeddings, and stores them in a Vector DB.  
- Enables semantic search and retrieval of emails or sheet records for downstream tasks.

**Contexual Retrieval RAG Flow using GrokCloud**  
- Implements a contextual-chunking pipeline with GrokCloud for more meaningful document segmentation.  
- Groups related text into context-aware chunks before embedding.  
- Improves retrieval-augmented generation (RAG) by providing richer, coherent context to the LLM.

**Custom ChatGPT Agent – Gmail & Calendar & Sheets**  
- Custom ChatGPT agent integrating Gmail, Google Calendar, and Sheets APIs.  
- Automates email parsing, event creation, and sheet updates in a single conversational interface.  
- Ideal for personal productivity and business workflow automation.

**Flowise to n8n via HTTP Request (CURL)**  
- Connects Flowise chatflows to n8n via HTTP requests or cURL.  
- Sends chatflow outputs to n8n webhooks for automation triggers.  
- Useful for chaining AI-driven responses with low-code workflows.

**Infranodus – Graph RAG**  
- Builds a semantic graph of documents using InfraNodus.  
- RAG queries traverse this graph to uncover hidden relationships and topic clusters.  
- Helps with knowledge discovery and complex information synthesis.

**Leads RAG Agent**  
- Ingests lead data and embeds it into a Pinecone vector database.  
- Supports fast semantic search and retrieval of potential customer leads.  
- Ideal for CRM enrichment and sales intelligence.

**Local RAG Agent – Ollama & PgVector – PG DB Manager**  
- Runs Ollama locally for inference with PgVector for vector embeddings.  
- Includes a Postgres DB manager to handle data ingestion and queries.  
- Provides a private, self-hosted RAG setup without cloud dependency.

**Local RAG Agent – Ollama & Qdrant**  
- Pairs local Ollama LLM inference with Qdrant vector storage.  
- Supports high-speed similarity search and context retrieval on local data.  
- Good for privacy-sensitive deployments needing on-prem solutions.

**Local RAG Agent – Ollama & Supabase**  
- Combines Ollama local LLM with Supabase’s managed Postgres and vector features.  
- Enables serverless, scalable RAG applications while keeping compute local.  
- Balances privacy with cloud convenience.

**Multi Agent RAG – Flowise**  
- Orchestrates multiple specialized agents through Flowise.  
- Agents handle retrieval, internet search, and content generation in parallel.  
- Great for complex tasks like research or multi-step problem solving.

**Multi Agent RAG – Serp API**  
- Multi-agent system enhanced by Serp API for live web searches.  
- Agents fetch current data and integrate it with vector retrieval results.  
- Useful for real-time intelligence and competitive analysis.

**Multi MCP Server – Zapier & Gmail Sheets**  
- Bridges multiple MCP servers with Zapier automations.  
- Syncs Gmail and Google Sheets data across connected apps.  
- Simplifies complex integrations with minimal coding.

**RAG GCP & Pinecone**  
- Implements a RAG pipeline using Google Cloud services for compute.  
- Stores embeddings in Pinecone for scalable vector search.  
- Suited for enterprise-level document retrieval and Q&A.

**RAG Q&A – Web Chatflow**  
- Web-based interface for asking natural-language questions over your data.  
- Uses a RAG backend to fetch and synthesize answers from indexed documents.  
- Great for knowledge bases, FAQs, or internal documentation.

**RAG Q&A – Web Chatflow Ollama**  
- Similar to the standard Web Chatflow but powered by a local Ollama model.  
- Provides private, offline Q&A capabilities with RAG.  
- Ideal when data must stay fully on-device.

**RAG Tool Agent – calculator + Brave + Writefile + OpenRouter**  
- An agent equipped with multiple tools: Brave for web search, a calculator, and file writing.  
- Routes model requests through OpenRouter for flexible LLM selection.  
- Handles tasks from data gathering to computation and file creation.

**RAG with Supabase + PostgreSQL**  
- Step-by-step tutorial to build a RAG solution using Supabase and Postgres.  
- Covers document ingestion, embedding generation, and query execution.  
- Good starting point for developers learning vector databases.

**Web Scraping Agent**  
- Automates website crawling by respecting robots.txt and using sitemaps.  
- Extracts and cleans data for downstream indexing or analysis.  
- Fits use cases like content aggregation or market research.

**Web Scraping RAG Multi Agent**  
- Multi-agent workflow that scrapes the web, embeds content, and provides retrieval.  
- Supports live data collection and on-demand Q&A.  
- Enables real-time insights from dynamic websites.

**Whatsapp AI Customer – Tickets Processing & SaleAgent**  
- WhatsApp chatbot for customer support and sales ticketing.  
- Processes audio messages, logs interactions in Supabase, and tracks leads.  
- Streamlines customer service and automates follow-ups.

---

### 🚀 Quick Start Guide

```
1. Open Flowise or n8n.
2. Click **Import Flow**.
3. Select any `.json` file from this repo.
4. Provide the required API keys (OpenAI, Pinecone, etc.) in the environment variables.
```





