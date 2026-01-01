# Chat with MySQL Database using LangChain & Groq

This repository contains a Python project that allows users to chat with a MySQL database using natural language. The system uses LangChain with the Groq LLM to translate questions into SQL, execute them, and return readable answers.

## Architecture


Below is the system architecture diagram:

![Chat with MySQL Architecture](architecture_diagram.svg)

## Features

- Natural language interface for MySQL databases
- SQL generation using LangChain
- Query execution and result retrieval
- Human-readable responses
- Tested with the Chinook sample database
- Database schema inspection

## Prerequisites

- Python 3.9+
- MySQL Server (local or remote)
- Chinook MySQL sample database
- Groq API key

## Setup

### 1. Clone the Repository

```bash
git clone https://github.com/Madhusanka-slc/chat-with-mysql.git
cd chat-with-mysql

### 2. Create Python Environment and Install Dependencies

```bash
# Using Conda
conda create -n chat-mysql python=3.12
conda activate chat-mysql
pip install -r requirements.txt

### 2. Create Environment File

# Copy env.example to .env
cp env.example .env   # On Windows, manually copy env.example to .env

# Add your Groq API key and any other required values in the .env file
