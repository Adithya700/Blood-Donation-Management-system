# Blood Donation Management System

## Project Overview

The **Blood Donation Management System** is a web-based application designed to simplify and streamline the management of blood donations and blood inventory. It provides a centralized platform for maintaining donor information, managing blood stock, recording donations and blood requests, and searching for eligible donors.

This project was developed as an academic mini project to gain practical experience in full-stack web development, database integration, and web application design.

---

# Features

* Add and manage donor information
* Track blood stock by blood group
* Record blood donations
* Manage blood requests
* Search for eligible donors
* Store and retrieve data using SQLite
* Simple and user-friendly web interface

---

# Objectives

* Maintain donor records in an organized manner.
* Track available blood stock for different blood groups.
* Record blood donations and blood requests efficiently.
* Enable quick searching of eligible donors.
* Reduce manual effort and improve data accuracy.

---

# Technologies Used

## Frontend

* HTML5
* CSS3

## Backend

* Python
* Flask

## Database

* SQLite


---

# Project Structure

```text
Blood-Donation-Management-System/
│
├── static/              # CSS files
├── templates/           # HTML templates
├── app.py               # Main Flask application
├── create_db.py         # Database creation script
└── README.md            # Project documentation
```

---

# Installation

## 1. Clone the Repository

```bash
git clone <repository-url>
cd Blood-Donation-Management-System
```

## 2. Install Dependencies

```bash
pip install flask
```

## 3. Create the Database

```bash
python create_db.py
```

## 4. Run the Application

```bash
python app.py
```

The application will be available at:

```text
http://127.0.0.1:5000
```

---

# Application Workflow

1. Register donor details.
2. Store donor information in the SQLite database.
3. Record blood donations.
4. Update blood stock automatically.
5. Search donors based on blood group.
6. Record blood requests.
7. View and manage available blood inventory.

---

# Database

The application uses SQLite as the database for storing:

* Donor Information
* Blood Stock
* Donation Records
* Blood Request Records

---

# Live Demo

Project Link:

https://blood-donation-management-system-3-9ze1.onrender.com

---

# Future Enhancements

* User authentication and role-based access
* Email and SMS notifications
* Blood donation appointment scheduling
* Hospital management integration
* Blood availability dashboard with charts
* Mobile-responsive user interface
* Admin analytics and reporting

---

# Team Members

* Adithya K S
* Ajina Joseph
* Adithya Babu
* Anjana Premkumar
* Abiya Biju

---

# Learning Outcomes

Through this project, the team gained practical experience in:

* Flask web application development
* CRUD operations
* SQLite database integration
* HTML and CSS frontend development
* Project organization
* Version control using Git and GitHub

---

# License

This project was developed for educational purposes as part of an academic mini project.
