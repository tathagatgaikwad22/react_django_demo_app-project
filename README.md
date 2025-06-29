# React Django Demo App

A full-stack demo application combining a React frontend with a Django backend. This project demonstrates how to build and connect a modern React user interface with a robust Django REST API.

---

## Table of Contents

- [Project Overview](#project-overview)  
- [Features](#features)  
- [Technologies Used](#technologies-used)  
- [Setup and Installation](#setup-and-installation)  
- [Running the Application](#running-the-application)  
- [Project Structure](#project-structure)  
- [API Endpoints](#api-endpoints)  
- [Contributing](#contributing)  
- [License](#license)  
- [Contact](#contact)  

---

## Project Overview

This project is a demo full-stack application that integrates React on the frontend with Django REST framework on the backend. It serves as a practical example for developers wanting to learn how to build modern web applications with these technologies.

---

## Features

- React-based responsive frontend  
- Django REST API backend  
- CRUD operations through API  
- Cross-Origin Resource Sharing (CORS) enabled  
- Demonstrates communication between React and Django  

---

## Technologies Used

**Frontend:**  
- React  
- Axios (for API calls)

**Backend:**  
- Django  
- Django REST Framework  
- Django CORS Headers  

---

## Setup and Installation

### Prerequisites

- Python 3.x  
- Node.js and npm  
- Git

### Backend Setup

1. Clone the repository:
   ```bash
   git clone https://github.com/tathagatgaikwad22/react_django_demo_app-project.git
   cd react_django_demo_app-project/backend

2. (Optional) Create and activate a virtual environment:

bash
	python -m venv venv
	source venv/bin/activate  # On Windows: venv\Scripts\activate

3. Install backend dependencies:

bash
	pip install -r requirements.txt

4. Apply migrations and start the Django server:

bash
	python manage.py migrate
	python manage.py runserver

### Frontend Setup

1. Open a new terminal window/tab and navigate to the frontend directory:

bash
	cd ../frontend

2. Install frontend dependencies:

bash
	npm install

3. Start the React development server:

bash
	npm start

### Running the Application

Backend server runs by default at: http://127.0.0.1:8000/
React frontend runs by default at: http://localhost:3000/

The React app will communicate with the Django backend API to fetch or post data.

### Project Structure
csharp

react_django_demo_app-project/
│
├── backend/                 # Django backend code
│   ├── backend/             # Django project settings
│   │   ├── __init__.py
│   │   ├── settings.py
│   │   ├── urls.py
│   │   └── wsgi.py
│   ├── core/                # Django app (API endpoints here)
│   │   ├── migrations/
│   │   ├── __init__.py
│   │   ├── admin.py
│   │   ├── apps.py
│   │   ├── models.py
│   │   ├── serializers.py
│   │   ├── tests.py
│   │   └── views.py
│   ├── manage.py
│   └── requirements.txt
│
├── frontend/                # React frontend code
│   ├── node_modules/
│   ├── public/
│   ├── src/
│   │   ├── components/
│   │   ├── App.js
│   │   ├── index.js
│   │   └── ...
│   ├── package.json
│   └── package-lock.json
│
└── README.md                # This file

## API Endpoints
(Add your API endpoint details here as needed)

## Contributing
Contributions are welcome! Please open an issue or submit a pull request for any improvements or bug fixes.

## License
This project is licensed under the MIT License. See the LICENSE file for details.

## Contact
Created by Tathagat Gaikwad — feel free to connect!

Email: tathagatgaikwad22@gmail.com
GitHub: tathagatgaikwad22
LinkedIn: https://www.linkedin.com/in/tathagat-gaikwad/
