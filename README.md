````markdown
# Chat with MySQL Database with LangChain & Groq

This project allows you to interact with a MySQL database using natural language queries powered by LangChain and the Groq LLM. It converts natural language questions into SQL, executes them on the database, and returns human-readable answers.

## Architecture Diagram

`Chat_with_Mysql.svg` (located in the same folder)

---

## Features

- Connects to a MySQL database (tested with the Chinook sample database)
- Converts natural language questions into SQL queries
- Executes SQL queries and fetches results
- Converts SQL results into natural language answers
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

### 1. Clone the Repository

```bash
git clone https://github.com/Madhusanka-slc/chat-with-mysql.git
cd chat-with-mysql
````

### 2. Install Libraries

```bash
pip install -r requirements.txt
```
