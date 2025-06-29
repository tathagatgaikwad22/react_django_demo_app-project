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
- Simple authentication setup (if applicable)  
- Demonstrates communication between React and Django  

---

## Technologies Used

**Frontend:**  
- React  
- Axios (for API calls)  
- React Router (if used)

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

   python -m venv venv
   source venv/bin/activate  # On Windows: venv\Scripts\activate

3. Install backend dependencies:

   pip install -r requirements.txt

4. Apply migrations and start the Django server:

   python manage.py migrate
   python manage.py runserver

## Frontend Setup
1. Navigate to the frontend directory:

   cd ../frontend

2. Install frontend dependencies:

   npm install

3. Start the React development server:

   npm start

## Running the Application
   
   Backend server runs by default at http://127.0.0.1:8000/
   React frontend runs by default at http://localhost:3000/
   The React app will communicate with the Django backend API to fetch or post data.

## Project Structure

react_django_demo_app-project/
│
├── backend/                # Django backend code
│   ├── manage.py
│   ├── app/                # Your Django app(s)
│   ├── requirements.txt
│   └── ...
│
├── frontend/               # React frontend code
│   ├── public/
│   ├── src/
│   ├── package.json
│   └── ...
│
└── README.md               # This file



## Contributing
Contributions are welcome! Please open an issue or submit a pull request for any improvements or bug fixes.

## License
This project is licensed under the MIT License. See the LICENSE file for details.

## Contact
Created by Tathagat Gaikwad — feel free to connect!

GitHub: tathagatgaikwad22

LinkedIn: https://www.linkedin.com/in/tathagat-gaikwad/

