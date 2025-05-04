# 🤖 Automated RAG Chatbot Workflow – n8n + Pinecone

This repository contains a Retrieval-Augmented Generation (RAG) chatbot workflow built using [n8n](https://n8n.io/) and powered by Pinecone for vector similarity search. The chatbot accepts user queries via webhook, retrieves relevant PDF document content, and generates responses using the OpenAI API.

## 🌟 Key Features

- 💬 Intelligent knowledge-based chatbot with RAG architecture
- 🌐 Webhook-based interface, ideal for web apps and internal tools
- 📚 Answers questions based on indexed PDF documents
- 🌍 Supports English and Bangla language queries
- 🔍 Uses **Pinecone** for high-performance vector similarity search
- 🧠 Integrated with **Langchain** for query routing and document retrieval
- ⚡ Generates contextual replies using **OpenAI GPT** models
- 🔧 Built with n8n for visual workflow automation and customization

## 🛠️ Technologies Used

- [n8n](https://n8n.io/) – Visual workflow automation
- [Pinecone](https://www.pinecone.io/) – Managed vector database for retrieval
- [Langchain](https://www.langchain.com/) – Query pipeline framework
- [OpenAI API](https://platform.openai.com/) – Response generation
- [FastAPI](https://fastapi.tiangolo.com/) – Backend for Langchain (optional)
- [Streamlit](https://streamlit.io/) – Optional UI

## 📁 Project Structure

