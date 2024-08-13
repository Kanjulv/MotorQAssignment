# MotorQAssignment

Vehicle-Driver Mapping System
Overview
The Vehicle-Driver Mapping System is a web application designed to manage and optimize the assignment of drivers to vehicles. The system provides a comprehensive solution that includes basic driver creation, vehicle-driver assignment, scheduling, conflict handling, and advanced features such as driver search based on location.

Features
Level 0: Basic Driver Creation and Vehicle-Driver Assignment
Driver Creation: Users can create and store driver profiles with essential details, including Driver ID, Name, Email, Phone Number, and Location.
Driver Search: Drivers can be searched by name and phone number.
Vehicle-Driver Assignment: Allows manual assignment and un-assignment of drivers to vehicles. A driver can only be assigned to one vehicle at a time.
Vehicle Information: Vehicle data (e.g., Vehicle ID, Make, Model, License Plate) is pre-populated and stored in the system.
Level 1: Time Scheduling and Assignment Conflict Handling
Time-Bound Assignments: The system supports scheduling, allowing drivers to be assigned to vehicles within specific timeframes (from timestamp A to timestamp B).
Conflict Handling: Prevents overlapping assignments by ensuring that a driver cannot be assigned to another vehicle during an existing assignment.
Level 2: Driver Assignment Requests and Acceptance
Assignment Requests: Drivers receive requests for vehicle assignments via the driver’s page.
Request Acceptance/Rejection: Drivers can accept or reject assignment requests. Multiple drivers can receive the same request, but only one can accept it.
Assignment Status: The system automatically updates the assignment status based on the driver's response.
Level 3: Driver Search and Assignment Based on Location
Location-Based Search: Users can search for available drivers based on proximity to a specified location.
Driver Availability: The system considers driver availability, location, and scheduling conflicts when suggesting drivers for assignments.
Work Hours: Drivers can have defined work hours set during enrollment and can only be booked within those hours.
Bonus Features
Dashboard Metrics: A dashboard displaying high-level metrics, including the top N booked vehicles for the day, week, and month.
Maps UI: A map interface to visualize available drivers based on their location.
Known Issues
Dashboard Redirection Issue: The dashboard functionality has a known issue where it keeps redirecting, causing an unstable user experience. This issue is under investigation and will be resolved in future updates.
Tech Stack
Frontend: React.js
Backend: Node.js, Express.js
Database: MongoDB
Mapping/Location Services: [Include any services used, e.g., Google Maps API]

NOTE - Dashboard Redirection Issue: The dashboard functionality has a known issue where it keeps redirecting, causing an unstable user experience. This issue is under investigation and will be resolved in future updates.
