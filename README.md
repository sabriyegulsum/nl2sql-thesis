# NL2SQL Thesis Project 🚀

## Overview

NL2SQL Thesis Project is a full-stack application that converts natural language questions into executable SQL queries using AI.

Users can ask questions in plain language such as:

- "List the top 3 suppliers"
- "Show the most expensive products"
- "Which customer placed the most orders?"

The system generates SQL queries automatically, executes them on PostgreSQL, and displays the results through a modern frontend interface.

---

# Tech Stack

## Frontend
- React
- Vite
- Tailwind CSS

## Backend
- Spring Boot
- Java
- REST API

## AI Service
- FastAPI
- Python
- LangChain
- OpenAI API

## Database
- PostgreSQL
- Docker

---

# System Architecture

Frontend (React)  
↓  
Backend API (Spring Boot)  
↓  
AI Service (FastAPI)  
↓  
PostgreSQL Database (Docker)

---

# Features

- Natural Language to SQL conversion
- AI-powered query generation
- PostgreSQL integration
- Full-stack architecture
- Dockerized database
- Interactive frontend UI
- REST API communication
- Relational database querying with JOIN support

---

# Database

The project includes relational e-commerce style datasets such as:

- Customers
- Products
- Orders
- Order Items
- Suppliers
- Product Suppliers
- Payments
- Reviews
- Shipments
- Categories
- Brands

CSV datasets are loaded into PostgreSQL using Docker.

---

# Installation

## 1. Clone Repository

```bash
git clone https://github.com/sabriyegulsum/nl2sql-thesis.git
cd nl2sql-thesis
```

---

## 2. Start PostgreSQL Docker Container

```bash
docker start tez-postgres
```

---

## 3. Run AI Service

```bash
cd /Users/sabriyesoyla/Desktop/nl2sql_tez
source ai_service/.venv/bin/activate
PYTHONPATH=$(pwd) uvicorn ai_service.app.main:app --host 127.0.0.1 --port 8001
```

---

## 4. Run Backend

```bash
cd backend
./mvnw spring-boot:run
```

---

## 5. Run Frontend

```bash
cd frontend
npm install
npm run dev
```

---

# Application URLs

| Service | URL |
|---|---|
| Frontend | http://localhost:5173 |
| Backend | http://localhost:8081 |
| AI Service | http://127.0.0.1:8001 |

---

# Example Queries

- "Top 3 suppliers"
- "Most expensive products"
- "Customer with the highest number of orders"
- "Most sold products"
- "Average product ratings"

---

# Project Goals

- Explore AI-powered database interaction
- Improve accessibility of SQL querying
- Build a scalable NL2SQL architecture
- Combine AI + Full Stack + Database technologies

---

# CV / Resume Description

AI-powered NL2SQL Full Stack Application developed using React, Spring Boot, FastAPI, PostgreSQL, and Docker. The system converts natural language questions into executable SQL queries and displays real-time database results through an interactive frontend.

---

# GitHub Repository

https://github.com/sabriyegulsum/nl2sql-thesis
