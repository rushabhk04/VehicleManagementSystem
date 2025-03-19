## 🚗 Vehicle Management System

## 📌 Overview
The Vehicle Management System is designed to streamline vehicle-related operations in an organization, reducing manual work and improving efficiency. The system enables better coordination between users, drivers, and employees while ensuring transparency and cost savings.

## 🔥 Features
User & Driver Management: Register, modify, and remove drivers and users.
Vehicle Tracking: Add, modify, and remove vehicles.
Journey Management: Start, modify, and end journeys.
Fuel & Maintenance Logs: Track fuel transactions and maintenance records.
Approval System: Admin approval for vehicle requests and user applications.
Authentication: Secure login/logout functionality.
Singleton Pattern Implementation: Ensures efficient and centralized control.

## 📁 Project Structure
cpp
Copy
Edit
src/
│── vehicle_management/
│   ├── add_driver.java
│   ├── add_journey.java
│   ├── add_maintenance.java
│   ├── add_private.java
│   ├── add_vehicle.java
│   ├── admin_cancel.java
│   ├── admin_modifydetails.java
│   ├── end_journey.java
│   ├── get_app.java
│   ├── local_vehicle.java
│   ├── login.java
│   ├── logout.java
│   ├── modify_driver.java
│   ├── modify_rate.java
│   ├── modify_vehicle.java
│   ├── newfuel_trans.java
│   ├── newvehicle_trans.java
│   ├── outs_approve.java
│   ├── p_entry.java
│   ├── register.java
│   ├── Singleton.java
│   ├── start_journey.java
│   ├── updatefuel_trans.java
│   ├── updatevehicle_trans.java
│   ├── user_application.java
│   ├── user_cancel.java
🛠️ Technologies Used
Programming Language: Java
Design Pattern: Singleton (Singleton.java)
Database: (Specify if applicable)
Frameworks/Libraries: (Specify if applicable)

## 🚀 Installation & Setup
Clone the Repository

sh
Copy
Edit
git clone https://github.com/rushabhk04/vehicle-management-system.git
cd vehicle-management-system
Compile the Java Files

sh
Copy
Edit
javac -d bin src/vehicle_management/*.java
Run the Application

sh
Copy
Edit
java -cp bin vehicle_management.MainClass  # Replace with actual main class

## 📖 Usage
User Registration: New users can register using register.java.
Driver Management: Admin can add, modify, or remove drivers using add_driver.java and modify_driver.java.
Vehicle Operations: Vehicles can be added, modified, or assigned via add_vehicle.java, modify_vehicle.java, and newvehicle_trans.java.
Journey Handling: Journeys can be started, modified, and ended using start_journey.java and end_journey.java.
Approval Process: Requests are approved via outs_approve.java.
