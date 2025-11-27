# FastAPI_Practice

**Backend Practice Project using FastAPI + SQLAlchemy**  

A simple project to practise building REST APIs using FastAPI and SQLAlchemy — implementing database models, CRUD operations (Create, Read, Update, Delete), and basic API endpoints.

## Features

- ✅ Basic API endpoints for CRUD operations  
- ✅ Database integration using SQLAlchemy (cloud based)  
- ✅ Data validation and serialization using Pydantic (`schemas.py`, `models.py`)  
- ✅ Simple project structure: `main.py`, `database.py`, `models.py`, `schemas.py`  
- ✅ Easy to run and extend — ideal for learning and prototyping  

## Getting Started

### Prerequisites

- Python 3.7+  
- `pip`  

### Installation & Run

```bash
# clone the repository
git clone https://github.com/Rkirthi1234/fast_api_practice.git
cd fast_api_practice

# install dependencies
pip install -r requirements.txt

# run the server (auto-reload on changes)
uvicorn main:app --reload

Open your browser at http://127.0.0.1:8000/docs to view interactive API documentation (Swagger UI) provided by FastAPI.

## Project Structure

fast_api_practice/
├── main.py         # Entry point — FastAPI app and route definitions
├── database.py     # Database setup and connection
├── models.py       # SQLAlchemy models (database schema)
├── schemas.py      # Pydantic schemas for request/response validation
├── requirements.txt

## Why this project:

This repository serves as a learning playground to get comfortable with backend API development using FastAPI and SQLAlchemy. It demonstrates the core backend workflow: how data is stored and managed, how CRUD operations work, and how to expose REST API endpoints.

Whether you are new to FastAPI or brushing up your backend skills — this project helps you understand how to build a simple, functional API backend from scratch.
