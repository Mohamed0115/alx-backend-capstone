# Task Manager API - ALX Backend Capstone

## Introduction
This is the final Capstone Project for the ALX Back-End Software Engineering programme. It is a robust RESTful API built with **Django** and **Django REST Framework**. The application allows users to manage tasks through Create, Read, Update, and Delete (CRUD) operations.

## Technologies Used
- **Language:** Python 3.x
- **Framework:** Django & Django REST Framework
- **Database:** SQLite (Default)
- **Architecture:** MVC / MVT
- **Tools:** Git, GitHub, VS Code

## Features
- **API Health Check:** Endpoint to verify system status.
- **Task Management:** Full CRUD capabilities for task items.
- **Browsable API:** Leverages DRF's web interface for easy testing.

## API Endpoints

| Method | Endpoint | Description |
| :--- | :--- | :--- |
| `GET` | `/status/` | Check API health |
| `GET` | `/tasks/` | List all tasks |
| `POST` | `/tasks/` | Create a new task |
| `GET` | `/tasks/<id>/` | Get details of a specific task |
| `PUT` | `/tasks/<id>/` | Update a specific task |
| `DELETE` | `/tasks/<id>/` | Delete a specific task |

## Setup & Installation

1. **Clone the Repository**
   ```bash
   git clone [<https://github.com/Mohamed0115/alx-backend-capstone>](https://github.com/Mohamed0115/alx-backend-capstone)
   cd alx-backend-capstone
