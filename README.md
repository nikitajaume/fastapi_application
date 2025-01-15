# Blog Application API Documentation

## Overview

The **Blog Application API** is a robust and efficient RESTful API built with FastAPI and SQLAlchemy. It provides CRUD (Create, Read, Update, Delete) functionality for managing users and posts in a blogging platform. The backend uses a MySQL database, leveraging SQLAlchemy ORM for database interactions.

## Features

- **User Management**: Create, read, update, and delete users.
- **Post Management**: Create, read, update, and delete blog posts associated with users.
- **Database Integration**: Uses MySQL with SQLAlchemy ORM for seamless database operations.
- **FastAPI Framework**: High-performance, modern web framework for building APIs.
- **Dependency Injection**: Modular database session management using FastAPI's `Depends`.

---

## Installation

### Prerequisites

- Python 3.7 or higher installed.
- MySQL database set up and running.
- `pip` package manager installed.

### Clone the Repository

```bash
git clone https://github.com/nikitajaume/fastapi_application.git
cd fastapi_application


# Blog Application API Documentation

## Overview

The **Blog Application API** is a robust and efficient RESTful API built with FastAPI and SQLAlchemy. It provides CRUD (Create, Read, Update, Delete) functionality for managing users and posts in a blogging platform. The backend uses a MySQL database, leveraging SQLAlchemy ORM for database interactions.

## Features

- **User Management**: Create, read, update, and delete users.
- **Post Management**: Create, read, update, and delete blog posts associated with users.
- **Database Integration**: Uses MySQL with SQLAlchemy ORM for seamless database operations.
- **FastAPI Framework**: High-performance, modern web framework for building APIs.
- **Dependency Injection**: Modular database session management using FastAPI's `Depends`.

---

## Installation

### Prerequisites

- Python 3.7 or higher installed.
- MySQL database set up and running.
- `pip` package manager installed.

### Clone the Repository

```bash
git clone https://github.com/nikitajaume/fastapi_application.git
cd fastapi_application

## Set Up the Environment

### Create and activate a virtual environment:

python -m venv venv
source venv/bin/activate    # On macOS/Linux
.\venv\Scripts\Activate     # On Windows

### Set up the database connection in database.py:

URL_DATABASE = 'mysql+pymysql://<username>:<password>@<host>:<port>/<database>'

Replace <username>, <password>, <host>, <port>, and <database> with your MySQL database details.
