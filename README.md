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
