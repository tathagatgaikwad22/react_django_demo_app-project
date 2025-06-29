# React Django Demo App

A simple full-stack demo application using React for the frontend and Django REST Framework for the backend.

## Features

- React-based UI
- Django REST API
- CRUD operations
- CORS enabled
- Easy to set up and run

## Tech Stack

- **Frontend:** React, Axios  
- **Backend:** Django, Django REST Framework, CORS Headers

## Setup Instructions

### Prerequisites

- Python 3.x  
- Node.js & npm  
- Git

### Backend Setup

```bash
git clone https://github.com/tathagatgaikwad22/react_django_demo_app-project.git
cd react_django_demo_app-project/backend

python -m venv venv
source venv/bin/activate  # Windows: venv\Scripts\activate

pip install -r requirements.txt
python manage.py migrate
python manage.py runserver

### Frontend Setup

1. Open a new terminal window/tab and navigate to the frontend directory:


  	cd ../frontend

2. Install frontend dependencies:

  	npm install

3. Start the React development server:

	  npm start

### Running the Application

Backend server runs by default at: http://127.0.0.1:8000/
React frontend runs by default at: http://localhost:3000/

The React app will communicate with the Django backend API to fetch or post data.

### Project Structure

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


## Contributing
Contributions are welcome! Please open an issue or submit a pull request for any improvements or bug fixes.

## License
This project is licensed under the MIT License. See the LICENSE file for details.

## Contact
Created by Tathagat Gaikwad — feel free to connect!

Email: tathagatgaikwad22@gmail.com
GitHub: tathagatgaikwad22
LinkedIn: https://www.linkedin.com/in/tathagat-gaikwad/
