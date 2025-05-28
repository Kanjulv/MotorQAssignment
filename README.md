# Vehicle-Driver Mapping System

## Overview
The **Vehicle-Driver Mapping System** is a comprehensive web application designed to manage and optimize the assignment of drivers to vehicles. It offers features from basic driver creation and vehicle assignment to advanced scheduling, conflict resolution, and location-based driver search. The system aims to streamline fleet management and enhance operational efficiency.

---

## Features

### Level 0: Basic Driver Creation and Vehicle-Driver Assignment
- **Driver Creation:** Create and store driver profiles with essential details including Driver ID, Name, Email, Phone Number, and Location.
- **Driver Search:** Search for drivers by name and phone number.
- **Vehicle-Driver Assignment:** Manually assign and un-assign drivers to vehicles. Each driver can only be assigned to one vehicle at a time.
- **Vehicle Information:** Pre-populated vehicle data (Vehicle ID, Make, Model, License Plate) stored in the system.

### Level 1: Time Scheduling and Assignment Conflict Handling
- **Time-Bound Assignments:** Assign drivers to vehicles within specific timeframes (from timestamp A to timestamp B).
- **Conflict Handling:** Prevents overlapping assignments ensuring a driver cannot be booked for multiple vehicles at the same time.

### Level 2: Driver Assignment Requests and Acceptance
- **Assignment Requests:** Drivers receive assignment requests through their page.
- **Request Response:** Drivers can accept or reject requests. Multiple drivers may receive the same request, but only one can accept.
- **Status Updates:** The system updates the assignment status automatically based on driver response.

### Level 3: Driver Search and Assignment Based on Location
- **Location-Based Search:** Search for available drivers based on proximity to a specified location.
- **Driver Availability:** Considers driver location, availability, and scheduling conflicts when suggesting drivers.
- **Work Hours:** Drivers have defined work hours during enrollment and can only be assigned within these hours.

### Bonus Features
- **Dashboard Metrics:** View high-level metrics such as the top N booked vehicles for the day, week, and month.
- **Maps UI:** Visualize available drivers on a map interface based on their location.

---

## Known Issues
- **Dashboard Redirection Issue:** The dashboard currently has a known issue where it keeps redirecting, causing unstable user experience. This is under investigation and will be fixed in future updates.

---

## Tech Stack
- **Frontend:** React.js
- **Backend:** Node.js, Express.js
- **Database:** MongoDB
- **Mapping/Location Services:** [Specify any used e.g., Google Maps API]

---

## Getting Started

### Prerequisites
- Node.js and npm installed
- MongoDB installed and running

### Installation
1. Clone the repository:
   ```bash
   git clone https://github.com/Kanjulv/Vehicle-Driver-Mapping-System.git
Navigate to the project directory:

bash
Copy
Edit
cd Vehicle-Driver-Mapping-System
Install dependencies for backend and frontend:

bash
Copy
Edit
cd backend
npm install
cd ../frontend
npm install
Setup environment variables as needed for database connections and API keys.

Running the Application
Start backend server:

bash
Copy
Edit
cd backend
npm start
Start frontend development server:

bash
Copy
Edit
cd frontend
npm start
Contributing
Contributions are welcome! Please open an issue or submit a pull request with your improvements.
