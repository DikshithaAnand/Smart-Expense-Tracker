## Smart Expense Tracker System

The Smart Expense Tracker System is a simple web-based application designed to manage personal income and expenses efficiently.

It helps users to:
- record income
- record expenses
- calculate remaining balance automatically
- view transaction history

This project is also developed as a DevOps mini project using GitHub, Docker, and Jenkins.

---

## Project Objective

The main objective of this project is:

- To enable users to easily monitor their income and expenses.
- To calculate total income, total expenses, and the remaining balance automatically.
- To demonstrate the implementation of DevOps practices using modern tools and technologies.

---

## 🚀 Features

- 💰 Add and manage income entries  
- 💸 Track and record expenses  
- 📊 View total income and expenses 
- 🧮 Automatically calculate remaining balance  
- 📜 Access complete transaction history  
- ❌ Delete transactions easily  
- 🎨 Clean, simple, and intuitive user interface 

---

## Technologies Used

### Frontend
- HTML
- CSS
- JavaScript

### Backend
- Python
- Flask Framework

### DevOps Tools
- GitHub
- Docker
- Jenkins

---

## Project Structure
```text
smart/
├── app.py
├── requirements.txt
├── Dockerfile
├── Jenkinsfile
├── .dockerignore
├── templates/
│   └── index.html
├── static/
│   ├── css/
│   │   └── style.css
│   └── js/
│       └── app.js
└── README.md
```
---

## How the Project Works

The user opens the Smart Expense Tracker application.
The user enters the transaction type, description, and amount.
The entered data is sent to the backend for processing.
The backend stores and manages the transaction details.
The system calculates the total income, total expense, and remaining balance.
The updated financial summary is displayed on the screen.

---

## Example

User enters:  
Income → Salary → 50000  
Expense → Food → 5000  

System shows:  
Total Income = 50000  
Total Expense = 5000  
Remaining Balance = 45000  

---

## Running the Project Using Docker

Step 1: Open Docker Desktop  
Open Docker Desktop and wait until it fully starts.  

Step 2: Open terminal in project folder  
cd Downloads  
cd smart  
cd smart  

Step 3: Check files  
dir  

Step 4: Build Docker image  
docker build -t smart-expense-tracker .  

Step 5: Run Docker container  
docker run -d -p 5000:5000 --name expense-tracker smart-expense-tracker  

Step 6: Check running container  
docker ps  

Step 7: Open application in browser  
http://localhost:5000  

---

## Useful Docker Commands

docker images  
docker ps  
docker stop expense-tracker  
docker start expense-tracker  
docker rm expense-tracker  

---

## If Container Already Exists

docker stop expense-tracker  
docker rm expense-tracker  
docker run -d -p 5000:5000 --name expense-tracker smart-expense-tracker  

---

## If Port 5000 Is Already Busy

docker run -d -p 5001:5000 --name expense-tracker smart-expense-tracker  

Open:  
http://localhost:5001  

---

## GitHub Usage

GitHub is used to store project code, manage versions, support collaboration, and integrate with DevOps tools.

---

## Docker Usage

Docker is used to package the application, include dependencies, and run it in a container.

---

## Jenkins Usage

Jenkins is used to automate build and deployment and support CI/CD pipeline.

---

## DevOps Flow

Code → GitHub → Docker → Jenkins → Running Application

---

## Advantages

- Easy to use  
- Useful in real life  
- Helps track spending  
- Automatically calculates balance  
- Beginner-friendly  
- Supports DevOps implementation  

---

## Limitations

- No login/signup  
- No database  
- Data is temporary  
- Basic version  

---

## Future Enhancements

- Implement a secure user login and authentication system.  
- Integrate a database for efficient data storage and management.  
- Add charts and graphs for better financial visualization.  
- Generate detailed reports for income and expenses.  
- Develop a mobile application for easy access on smartphones.  
- Deploy the project to the cloud for better scalability and availability.    

---

## Conclusion

Smart Expense Tracker System is a simple and useful web application that helps users manage income and expenses.  
It also demonstrates DevOps concepts using GitHub, Docker, and Jenkins.  

Team Members:
Dikshitha A
Gangambika DV
Srujana
Vasudev

