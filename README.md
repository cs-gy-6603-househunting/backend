# RoomScout 🏠

### A Student-Focused Real Estate Platform

**RoomScout** is a housing platform built to help **international students** in NYC find suitable accommodations with ease. It integrates key student-centric features, including verification, filters for key housing needs, and seamless property management.

---

## 🚀 Features

- **🏡 Lessee Profile Setup:** Create housing preferences (location, guarantor requirements, etc.)
- **🎓 Student Verification:** Authenticate via university email for eligibility
- **📌 Property Listings:** Lessors can post detailed listings with images and videos
- **🔍 Advanced Search & Filters:** Find properties by price, distance, amenities
- **❤️ Wishlist Feature:** Save and compare properties
- **📊 Safety Indicators:** Proximity to subway, laundromats, and crime rates

---

## 📊 Tech Stack

- **Backend:** Python, Flask/FastAPI, PostgreSQL
- **Frontend:** React.js, Next.js, TailwindCSS
- **Authentication:** Firebase Auth, JWT
- **Testing:** Jest, Pytest (87% Code Coverage)
- **Infrastructure:** AWS EC2, Docker, CI/CD

---

## 🛠 Development & Testing

- **Agile Development:** Scrum methodology (153 Story Points, 24 User Stories)
- **Unit Tests:** 32 (Jest + Pytest)
- **Load Testing:** Locust (110ms median response time, 0.21% failure rate)

---

## 📈 Performance Benchmarks

| Metric | Value |
|--------|------|
| Median Response Time | 110ms |
| Total Requests | 38,000 |
| Failure Rate | 0.21% |
| Requests per Second | 25.4 |

---

## 📌 Contributors

- **Akshat Singh** - Product Owner
- **Dhruv Topiwala** - Backend
- **Aninda Ghosh** - Backend
- **Subhrajit Dey** - Backend
- **Manamrit Singh** - Frontend

---

## 🛠 Setup & Installation

1. **Clone the Repository**
   ```sh
   git clone https://github.com/your-repo/roomscout.git
   cd roomscout
  

#  RoomScout App - Backend

  

This is the backend repository for the **RoomScout App**, built using Django. This app allows users to create profiles, search for property listings, manage wishlists, and interact with listings. It is designed to facilitate easy setup and contribution for new developers.

  

##  Table of Contents

  

-  [Tech Stack](#tech-stack)

-  [Getting Started](#getting-started)

-  [Prerequisites](#prerequisites)

-  [Installation](#installation)

-  [Running the Server](#running-the-server)

-  [Contributing](#contributing)

  

##  Tech Stack

  

-  **Language**: Python

-  **Framework**: Django

-  **Database**: PostgreSQL (default, but can be configured)

-  **Environment Management**: `venv` or `virtualenv`

-  **API Documentation**: Django REST Framework

  

##  Getting Started

  

###  Prerequisites

  

Make sure you have the following installed on your system:

  

-  Python 3.8+

-  `git`

  

###  Installation

  

1.  **Clone the repository**:


	``git clone https://github.com/cs-gy-6603-househunting/backend.git && cd backend``

2.  **Create a virtual environment**:

	`python3 -m venv venv`

3.  **Activate the virtual environment**:

-  On macOS/Linux:

	`source venv/bin/activate`

-  On Windows:

	`venv\Scripts\activate`

4.  **Install dependencies**:

	`pip install -r requirements.txt`

  

###  Running the Server

  

Start the Django development server:

  

`python manage.py runserver`

  

The server will start on `http://127.0.0.1:8000/`.

  

###  Running Tests

  

To run the tests, use:

  

`pytest ...`

  
  

##  Contributing

  

We welcome contributions to improve the RoomScout App! To contribute:

  

1.  **Fork the repository** and create your branch:

	`git checkout -b feature/your-feature-name`

2.  **Make your changes** and **commit** them:

	`git commit -m "Add your commit message here"`

3.  **Push to your forked repository**:

	`git push origin feature/your-feature-name`

4.  **Create a pull request** against the `develop` branch of the original repository.

  

###  Code Style Guidelines

  

-  Use **black** formatter regularly, especially before pushing your code to a branch.

-  Follow **PEP 8** for Python code style.

-  Use **docstrings** for methods and classes.

-  Ensure **tests** are written for new features or changes.
