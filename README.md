# GenAI_SQL_Intern_Task_Csireesha

**Submission for GenAI Internship Task (VIT - Anarix.ai)**  
**AI-Powered SQL Assistant using Gemini + SQLite + Jupyter/Colab**

---

## Project Title
**Build an AI Agent to Answer E-Commerce Data Questions**

---

## Project Overview

This project builds an AI assistant that:
- Understands natural language questions
- Uses **Google's Gemini (via API)** to convert them into SQL queries
- Executes those queries on structured **e-commerce datasets**
- Returns **clear results** and **visualizations**
- *(Bonus)* Adds graphs like bar charts and pie charts for better insights

---

## Datasets Used

The following datasets were uploaded and used in the project:
1.  `Product-Level Ad Sales and Metrics`
2.  `Product-Level Total Sales and Metrics`
3.  `Product-Level Eligibility Table`

These are converted to SQLite tables:
- `adsales`
- `totalsales`
- `eligibility`

---

## Task Objective

The agent should:
- Accept a natural language question
- Translate it into a **valid SQL query**
- Execute it on an **SQLite database**
- Return clean, human-readable answers
- (Bonus) Create **charts** for selected queries

---

## Tech Stack

| Tool / Library        | Description                          |
|------------------------|--------------------------------------|
| `Python`               | Core language                       |
| `Google Colab`         | Development environment             |
| `SQLite3`              | Embedded database engine            |
| `Pandas`               | DataFrame operations                |
| `Google Generative AI` | Used Gemini API for SQL generation  |
| `Matplotlib`           | Chart plotting                      |
| `dotenv`               | Secure environment variable loading |

---

### Upload Required Files
Upload the 3 provided datasets using:
```python
from google.colab import files
uploaded = files.upload()
