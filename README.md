📌 Lead Capture & Management System
🧠 Overview
This project is a full-stack lead capture and management system built with Flask. It simulates how lead ads flow into CRM platforms by accepting user input, validating it on the backend, persisting it in a relational database, and exposing REST APIs for retrieval.

🛠️ Tech Stack
* Backend: Python, Flask 
* Frontend: HTML, CSS, JavaScript 
* Database: SQLite 
* Architecture: RESTful API design 

🏗️ Architecture & Data Flow

User Input (HTML Form)
        ↓
JavaScript (Fetch API)
        ↓
Flask REST API
        ↓
Validation & Error Handling
        ↓
SQLite Database
        ↓
API Response
        ↓
Dynamic UI Update

✨ Features
✅ Lead Ingestion
* Accepts name, email, and company 
* Backend validation prevents invalid or incomplete data 
✅ Persistent Storage
* Uses SQLite for relational storage 
* Database schema initializes automatically at application startup 
✅ REST API Endpoints
Method	Endpoint	Description
POST	/add_lead	Add a new lead
GET	/leads	Retrieve all leads
✅ Error Handling
* Returns appropriate HTTP status codes 
* Handles invalid input and database errors gracefully 
✅ Dynamic Frontend
* Asynchronous data fetching 
* Real-time UI updates without page refresh 
* Styled UI with modern CSS 

🚀 Getting Started
1. Clone the repository

git [clone https://github.com/your-username/lead-capture-system.git](https://github.com/kyraprak/lead-manager.git)
cd

2. Install dependencies

pip install flask
3. Run the application

python app.py
4. Open in browser

http://127.0.0.1:5000/

🧪 Example API Response

{
  "message": "Lead added successfully"
}
Error response:

{
  "error": "Invalid email format"
}

📈 Future Enhancements
* Authentication & authorization 
* Update/delete lead endpoints 
* PostgreSQL migration 
* Deployment to cloud (Render, Railway) 
* Analytics dashboard 

💼 Why This Project Matters
This project demonstrates:
* Full-stack data flow 
* REST API design 
* Backend validation 
* Relational database usage 
* Real-world system architecture 
It mirrors how lead ads integrate with CRM systems in production environments.

👤 Author
Kyra Aspiring Software Engineer | Backend & Full-Stack Development
