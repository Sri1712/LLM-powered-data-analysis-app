# Build with AI: LLM-Powered Data Analysis App (Python + Streamlit)

This repository contains my implementation of the LinkedIn Learning course:  
**“Build with AI: LLM-Powered Data Analysis App Using Python and Streamlit”** by Maggie Ma.

## 📌 Overview

This project demonstrates how to build a lightweight AI-powered data analysis application that allows users to:

- Upload datasets (CSV, etc.)
- Ask questions in natural language
- Automatically generate Python or SQL code using an LLM
- Execute the code and return insights

The goal is to bridge the gap between technical and non-technical users by enabling intuitive data exploration.

---

## 🚀 Features

- 📂 Upload structured datasets  
- 💬 Natural language query interface  
- 🤖 LLM-powered code generation (Python / SQL)  
- 📊 Automated data analysis and insights  
- ⚡ Interactive UI built with Streamlit  

---

## 🛠️ Tech Stack

- Python  
- Streamlit  
- Pandas  
- OpenAI API  
- (Optional) SQL support  

---

## 🧠 How It Works

1. User uploads a dataset  
2. User enters a question in plain English  
3. The app sends the query + dataset context to an LLM  
4. The LLM generates executable code  
5. The app runs the code securely  
6. Results are displayed in the UI  

---

## 📦 Installation

```bash
git clone https://github.com/your-username/llm-data-analysis-app.git
cd llm-data-analysis-app
pip install -r requirements.txt
