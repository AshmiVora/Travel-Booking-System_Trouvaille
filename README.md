# Travel-Booking-System_Trouvaille
A  web application designed to streamline travel planning and ticket booking. Ideal for users seeking an intuitive yet powerful way to book flights, trains, buses, cruises and accommodations.

---

## Project Overview
Trouvaille is a full-stack travel booking management system designed to facilitate user-friendly, real-time travel planning and reservation. The system allows users to browse destinations, book trips, and manage their travel data through a clean, modern interface supported by a secure backend. The project integrates both frontend and backend components, along with a relational database schema, to simulate a real-world travel platform.

This project was developed as part of an academic submission focused on database-driven web application development and backend integration.

---

## Features
- **User registration and login functionality**
- **Display of travel destinations and booking options**
- **Real-time interaction with a backend database**
- **Dynamic routing and modular controller architecture**
- **Structured MySQL database schema for managing users, bookings, and destinations**
- **Organized MVC architecture in the backend**

---

## Technologies Used

### Frontend
- HTML  
- CSS  
- JavaScript  

### Backend
- Node.js  
- Express.js  

### Database
- MySQL  

### Other Tools and Libraries
- Nodemon (for backend development)    
- MySQL2  

---

##  Project Structure

```yaml
travelbooking/
│
├── trouvaille/
│   ├── backend/              # Express.js server and routing
│   ├── node_modules/         # Node.js dependencies
│   ├── public/               # Frontend files (HTML, CSS, JS)
│   ├── screenshots/          # Project screenshots (homepage, destinations, bookings)
│   ├── package.json          # Node.js project configuration
│   ├── package-lock.json     # Dependency lock file
│   └── tr.sql                # MySQL database schema

```
## Screenshots

### Homepage
![Homepage Screenshot](screenshots/homepage.png)

### Login Page
![Login Screenshot](screenshots/login.png)

### Booking Interface
![Booking Screenshot](screenshots/bookings.png)

##  Installation Instructions
### Prerequisites
- Node.js (v14+ recommended)
- MySQL Server

### Setup Steps

1. **Clone the repository:**

```bash
git clone https://github.com/AshmiVora/travelbooking.git
cd travelbooking/trouvaille
```

2. **Install backend dependencies:**
``` bash
    cd backend
    npm install
```

3. **Set up the MySQL database:**
- **Create a MySQL database.**
- **Import the tr.sql file into your database.**
- **Update the .env file (or backend/database.js) with your MySQL credentials:**

4. **Start the backend server:**
``` bash
   node server.js
```
By default the backend runs on: http://localhost:3000


---

## Usage
- **Navigate to the frontend interface.**
- **Register or log in as a user.**
- **Browse available destinations**
- **Select trips and make bookings.**

---

## License
This project is licensed under the Creative Commons Attribution-NonCommercial 4.0 International License.
Commercial use is not permitted.
Refer to LICENSE.md for more details.

---
## Acknowledgments
- Developed as part of an academic curriculum  
- [Node.js Documentation](https://nodejs.org/en/docs)  
- [MySQL Documentation](https://dev.mysql.com/doc/)  
 

