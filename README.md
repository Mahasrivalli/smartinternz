 ✈️ FlightFinder: Navigating Your Air Travel Options

 📌 Introduction

**Project Title:** FlightFinder: Navigating Your Air Travel Options


🎯 Purpose

FlightFinder is a **MERN stack web application** developed to simplify the flight booking process. It allows users to search, compare, and book flights based on their schedule, preferences, and budget.

 👤 User Features

* User registration and login
* Flight search with filters:

  * Price
  * Class
  * Stops
  * Airlines
* Seat selection
* Booking summary and confirmation

 🛠️ Admin Features

* Add and manage flights
* View bookings
* Admin dashboard

 💳 Additional Features

* Secure payment integration (test mode)
* Responsive UI



 🧑‍💻 My Contributions

* Designed and developed the **full-stack application** using MERN stack
* Implemented **user authentication using JWT**
* Built REST APIs for flights, users, and bookings
* Designed MongoDB schemas for structured data handling
* Developed responsive UI using React
* Integrated frontend with backend APIs using Axios
* Implemented filtering and search functionality

 🎨 Frontend (React)

* Component-based design
* Pages for search, booking, login
* State management using React Hooks
* API calls using Axios



 ⚙️ Backend (Node.js + Express)

* RESTful APIs
* JWT authentication
* Middleware for protected routes

**Main Routes:**

* `/api/users`
* `/api/flights`
* `/api/bookings`
* `/api/admin`



🗄️ Database (MongoDB)

* Collections:

  * Users
  * Flights
  * Bookings
* Mongoose for schema and queries




 📌 Prerequisites

* Node.js
* MongoDB
* Git
 📥 Installation

```bash
git clone https://github.com/your-username/flightfinder.git
cd flightfinder
 🔧 Backend Setup

```bash
cd server
npm install
npm start
 🎨 Frontend Setup

```bash
cd client
npm install
npm start


 🔐 Environment Variables (.env)
env
MONGO_URI=your_mongodb_uri
JWT_SECRET=your_jwt_secret
```




### Client


client/
 ├── src/
 │   ├── components/
 │   ├── pages/
 │   ├── App.js
 │   └── index.js


### Server


server/
 ├── controllers/
 ├── routes/
 ├── models/
 ├── middleware/
 └── server.js




Backend

```bash
cd server
npm start


Frontend

```bash
cd client
npm start



User

* `POST /api/users/register`
* `POST /api/users/login`

Flights

* `GET /api/flights`
* `GET /api/flights/:id`

Bookings

* `POST /api/bookings`

Admin

* `POST /api/admin/flights`

🔐 Authentication

* JWT-based authentication
* Protected routes using middleware
* Secure API access

🎨 UI Features

* Clean and responsive design
* Search with filters
* Seat selection interface
* Booking confirmation

🧪 Testing

* API testing using Postman
* Manual testing

⚠️ Known Issues

* Payment integration in test mode
* Performance can be improved

🔮 Future Enhancements

* Real-time flight API integration
* Email notifications
* Mobile app (React Native)



🎯 Key Highlights

* Full-stack MERN project
* Authentication & role-based features
* Real-world application concept
* Clean and modular code
