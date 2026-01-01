# Natural Language Database Chat with LangChain & Groq

This project allows you to interact with a MySQL database using natural language queries powered by LangChain and the Groq LLM. It converts natural language questions into SQL, executes them on the database, and returns human-readable answers.

---

## Features

- Connects to a MySQL database (tested with Chinook sample database)
- Converts natural language questions to SQL queries
- Executes SQL queries and fetches results
- Converts SQL results to natural language answers
- Interactive chat function for asking your own questions
- Schema inspection to understand database structure

---

## Prerequisites

- Python 3.9+
- MySQL Server running locally or accessible remotely
- Chinook MySQL sample database loaded (see **Database Setup**)
- Groq API key (sign up at [Groq Console](https://console.groq.com))

---

## Setup Instructions

### 1. Clone the repository

```bash
git clone <your-repo-url>
cd <your-repo-folder>
