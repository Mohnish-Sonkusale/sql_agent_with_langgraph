# 🧠 SQL Agent with LangGraph

This project demonstrates an agentic AI system using **LangGraph**, **LangChain**, and **GROQ’s LLaMA 3 model** to interact with a SQLite database via natural language.

It converts user queries into SQL, checks and corrects them, executes them, and returns accurate answers based on database contents.

---

## ✨ Features

- ✅ Converts natural language to SQL queries
- ✅ Double-checks and corrects SQL before execution
- ✅ Uses **LangGraph** to manage agentic flow
- ✅ Integrates **GROQ’s LLaMA 3** via `langchain_groq`
- ✅ Supports schema inspection and error fallback
- ✅ Reads secrets from `.env`

---

## 🛠 Tech Stack

- `LangChain`
- `LangGraph`
- `langchain_groq`
- `SQLite`
- `Python 3.10+`
- `dotenv` for secret management

---

## 🚀 Getting Started

Follow these steps to set up the project locally:

### 1️⃣ Clone the Repository

```bash
git clone https://github.com/Mohnish-Sonkusale/sql_agent_with_langgraph.git
cd sql_agent_with_langgraph

## 🔧 Setup Summary

```bash
# 1. Create and activate virtual environment
python -m venv myenv
myenv\Scripts\activate         # On Windows
# or
source myenv/bin/activate      # On macOS/Linux

# 2. Install dependencies
pip install -r requirements.txt

# 3. Create a .env file with your GROQ API key
echo GROQ_API_KEY=your_api_key_here > .env

# 4. Run the application in any IDE
sql_agent_with_langgraph.ipynb
