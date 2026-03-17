# FoodHub Chatbot (LLM + SQL Agent)

**Program:** UT Austin Post Graduate Program in Generative AI for Business Applications  
**Course:** Business Applications with LLMs  

---

## 📌 Project Overview

This project builds an AI-powered chatbot for a food ordering system using Large Language Models (LLMs), SQL agents, and guardrails.

The chatbot allows users to query order information in natural language while ensuring safe, accurate, and controlled responses through input and output guardrails.

The goal is to demonstrate how Generative AI can be used in real business applications to automate customer support and database queries.

---

## 🎯 Objectives

- Build a chatbot using LLM + SQL Agent
- Retrieve order data from a database using natural language
- Implement input and output guardrails
- Prevent unsafe or invalid responses
- Demonstrate end-to-end chatbot workflow

---

## 🧠 Key Features

- LLM-based chat agent
- SQL database integration
- Tool-based agent workflow
- Input guardrails
- Output guardrails
- Conversational query handling
- Safe response filtering

---

## 📂 Repository Structure

FoodHubChatBot/
│
├── Dalal_Aayush_FoodHub_Chatbot_FullCode_Notebook.ipynb
├── Dalal_Aayush_FoodHub_Chatbot_FullCode_Notebook.html
├── customer_orders.db
├── Project 3 FAQ.txt
├── FoodHub_Project_Template.pptx
└── README.md

---

## ⚙️ Technologies Used

- Python
- Large Language Models (LLMs)
- LangChain / Agents
- SQL Database
- SQLite
- Prompt Engineering
- Guardrails
- Jupyter Notebook

---

## 🗄 Database

The chatbot connects to a SQLite database containing customer order information.

File:
customer_orders.db

The SQL agent allows the model to retrieve order details using natural language queries.

Example queries:
- Show details for order ID O12486
- What items are in this order?
- Cancel my order

---

## 🤖 Chatbot Workflow

User Input  
→ Input Guardrail  
→ LLM Processing  
→ SQL Agent (if needed)  
→ Output Guardrail  
→ Final Response  

This ensures safe and reliable chatbot behavior.

---

## 🚀 How to Run

1. Clone the repository

git clone https://github.com/aad6383/FoodHubChatBot.git

2. Open Notebook in Google Colab

3. Run each Cell in the notebook

---

## 💡 Use Case

This system can be used for:

- Customer support automation
- Order tracking chatbot
- AI help desk
- Conversational database queries
- Business AI assistants

---

## 📚 Program Information

UT Austin  
Post Graduate Program in Generative AI for Business Applications  
Business Applications with LLMs – Chatbot Project

---

## 👤 Author

Aayush Dalal  
MS Data Science / Machine Learning
