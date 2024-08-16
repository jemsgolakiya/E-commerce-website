E-Commerce Website

An advanced E-commerce platform built with React for the frontend and Django for the backend, using SQLite as the database. This project serves as a full-featured online store with product browsing, shopping cart, and order processing functionalities. The admin panel provides tools for managing products, users, and orders.

This E-commerce website is designed to provide a smooth shopping experience for users. The frontend is developed using React, ensuring a responsive and dynamic user interface. The Django backend manages the business logic, data handling, and provides a RESTful API to interact with the frontend. SQLite is used as the database, making the setup lightweight and easy to deploy.

Features

User Authentication: Secure user registration, login, and logout functionality.

Product Management: Users can browse, search, and filter products.

Shopping Cart: Add, update, and remove products from the cart.

Order Management: Process and track orders with a detailed order summary.

Admin Dashboard: Admin users can manage products, orders, and user data.

Responsive Design: Optimized for both desktop and mobile devices.

Technology Stack

Frontend

•	React: A JavaScript library for building user interfaces.

•	React Router: For handling routing within the application.

•	Axios: For making HTTP requests to the backend API.

•	Bootstrap: For responsive and modern UI design.

Backend

•	Django: A high-level Python web framework for building secure and maintainable websites.

•	Django REST Framework: For building robust RESTful APIs.

•	SQLite: A lightweight, file-based database used for data storage.

Tools

•	Git: Version control to track code changes.

•	GitHub: Repository hosting service for version control and collaboration.

How to Setup and Installation

Prerequisites

Ensure you have the following installed:

•	Node.js and npm (for frontend development)

•	Python 3.x and pip (for backend development)

•	Git (for version control)


Backend Setup (Django)

1.	Create and activate a virtual environment:

2.	Install required Python packages:

      •	pip install -r requirements.txt

3.	Apply database migrations:

      •	python manage.py migrate

4.	Create a superuser for the admin panel:

      •	python manage.py createsuperuser

5.	Start the Django development server:

      •	python manage.py runserver

Frontend Setup (React)

1.	Navigate to the frontend directory:

      •	cd frontend

2.	Install required Node packages:

      •	npm install

3.	Start the React development server:

      •	npm start

