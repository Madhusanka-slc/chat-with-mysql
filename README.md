# Chat with MySQL Database using LangChain & Groq

This repository contains a Python project that allows users to chat with a MySQL database using natural language. The system uses LangChain with the Groq LLM to translate questions into SQL, execute them, and return readable answers.

## Architecture

The architecture diagram is included in the root directory:

- Chat_with_Mysql.svg

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

### Clone the Repository

```bash
git clone https://github.com/Madhusanka-slc/chat-with-mysql.git
cd chat-with-mysql
