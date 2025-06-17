# TDS_Project1
This project implements a Retrieval-Augmented Generation (RAG) system that answers questions related to the IIT Madras Tools for Data Science (TDS) course. It uses a FastAPI backend and a local SQLite knowledge base containing Discourse posts and markdown content.

## Features

- Answers course-related queries using GPT with context from a local knowledge base.
- Stores semantic chunks from Discourse and markdown documents in SQLite with embeddings.

## Architecture

User Question → Embedding → Vector Search → Top Chunks → GPT Completion → Final Answer + Source Links

## Technologies Used

- FastAPI
- SQLite for document storage
- AIPipe for embedding and completion

## Setup Instructions

### 1. Clone the repository

```bash
git clone https://github.com/your-username/tds-virtual-ta.git
cd tds-virtual-ta
