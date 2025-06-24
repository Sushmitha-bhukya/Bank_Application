# Bank Application using Docker

🏦 Banking Web Application
A lightweight, browser-based banking application built with Flask and SQLite. This project simulates basic banking operations such as account creation, balance inquiry, deposit, and withdrawal.

✅ Objective
To create a minimal, functional web application that mimics core banking operations using Python, with an intuitive user interface and lightweight backend suitable for educational and demo purposes.

🧰 Tech Stack
1. Frontend: HTML (rendered via render_template_string), CSS (inline)
2. Backend: Python (Flask)
3. Database: SQLite3 (local file bank.db)
4. Others: HTTP Forms for user interaction

📋 Steps Included
1. Database Initialization
   On the first run, creates a SQLite database with a table for storing account data (ID, name, balance).
2. Routing and Functionality
   1. /create: Create a new account with name and initial balance.
   2. /balance: View balance by entering account ID.
   3. /deposit: Add funds to an account.
   4. /withdraw: Withdraw funds from an account (with balance check).
   5. /statement: Placeholder for future statement feature.
3. Dynamic HTML UI
    1. Built-in layout using inline HTML and CSS rendered through Flask.
    2. All forms are handled through HTTP POST and updated live.
   
🚀 How to Run
1. Install dependencies
    pip install flask
2. Run the application
    python <filename>.py
3. Access the app
    Open browser and go to: http://localhost:5005
   
📌 Additional Notes
1. All account operations require an Account ID (auto-generated during creation).
2. The application uses a flat file database (bank.db), ideal for learning and prototyping.
3. Statement feature is under development (placeholder exists).


