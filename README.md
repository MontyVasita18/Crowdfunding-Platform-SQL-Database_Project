# 💡 Crowdfunding Platform – SQL Database Project

## 📌 Project Overview
This project models a crowdfunding platform using SQL. It simulates core platform functionality like user roles (backers, creators, admins), project creation, pledging, reward distribution, and transaction tracking. The goal is to analyze platform performance and user behavior using relational database design and SQL queries.

## ⚙️ Technologies Used
- **Database:** MySQL
- **Query Language:** SQL (DDL, DML, Joins, Aggregations, Subqueries)
- **Tools:** MySQL Workbench / phpMyAdmin

## 🗃️ Database Schema
The database contains 10+ interrelated tables with appropriate primary/foreign keys and constraints.

### Main Tables:
- **Users**: Backers, creators, admins with signup timestamps  
- **Projects**: Includes goal amount, category, timeline, and status  
- **Pledges**: Tracks who pledged how much to which project  
- **Rewards**: Linked to projects with minimum pledge thresholds  
- **Transactions**: Records payment details and status  
- **Comments, Followers, Notifications, Updates**: Enhance user engagement

![ER Diagram](#) *(https://github.com/MontyVasita18/Crowdfunding-Platform-SQL-Database_Project/blob/main/New%20Schema.pdf)*

## 🧠 Business Insights & Sample Queries

### 🔍 User Insights
- Track user growth and roles  
- Find top creators by project success rate  

### 📈 Project & Category Insights
- Success/failure rate of projects by category  
- Average project duration and funding goals  

### 💸 Pledge & Reward Insights
- Total and average pledge amount  
- Most popular rewards and backers  

### 💳 Transaction Analysis
- Completed vs failed payments  
- Most used payment methods and revenue  

## 🛠️ How to Run

1. Clone the repository:
```bash
git clone https://github.com/yourusername/crowdfunding-sql-project.git
