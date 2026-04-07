# Smart Expense Tracker System

Smart Expense Tracker System is a simple web-based application used to manage personal income and expenses.

It helps users to:
- record income
- record expenses
- calculate remaining balance automatically
- view transaction history

This project is also developed as a DevOps mini project using GitHub, Docker, and Jenkins.

---

## Project Objective

The main objective of this project is:
- to help users track their income and expenses easily
- to calculate total income, total expense, and remaining balance
- to demonstrate DevOps implementation using modern tools

---

## Features

- Add Income
- Add Expenses
- View Total Income
- View Total Expense
- View Remaining Balance
- View Transaction History
- Delete Transactions
- Simple and Attractive User Interface

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

User opens the Smart Expense Tracker application.  
User enters transaction type, description, and amount.  
Data is sent to backend.  
Backend processes the data.  
System calculates total income, total expense, and remaining balance.  
Updated data is shown on the screen.

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

- Add login system  
- Add database  
- Add charts  
- Add reports  
- Add mobile app  
- Deploy to cloud  

---

## Conclusion

Smart Expense Tracker System is a simple and useful web application that helps users manage income and expenses.  
It also demonstrates DevOps concepts using GitHub, Docker, and Jenkins.  
