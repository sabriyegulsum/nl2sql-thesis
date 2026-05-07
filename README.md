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
