🧩 Echo Board Project Management Tool


A modern, full-stack project management application built with React and Python Flask, designed to streamline team collaboration and task tracking.

🚀 Features

User Authentication: Secure login and registration system.

Task Management: Create, update, and delete tasks with ease.

Real-Time Updates: Instant synchronization across all users.

Mobile-Friendly: Responsive design for seamless use on any device.

🔧 Tech Stack
Frontend: React, Redux, Axios

Backend: Python, Flask, SQLAlchemy

Database: PostgreSQL

Authentication: JWT (JSON Web Tokens)

Styling: Bootstrap 5

Deployment: Render, Gitpod

🛠️ Installation
Clone the repository
bash
Copy
Edit
git clone https://github.com/robertaval/robertaval_Echo_Board_Project_Mgmt_Tool.git
cd robertaval_Echo_Board_Project_Mgmt_Tool
Backend Setup
Navigate to the backend directory:

bash
Copy
Edit
cd backend
Install dependencies:

bash
Copy
Edit
pip install -r requirements.txt
Set up environment variables by copying the example file:

bash
Copy
Edit
cp .env.example .env
Apply database migrations:

bash
Copy
Edit
flask db upgrade
Run the Flask server:

bash
Copy
Edit
flask run
Frontend Setup
Navigate to the frontend directory:

bash
Copy
Edit
cd ../frontend
Install dependencies:

bash
Copy
Edit
npm install
Start the development server:

bash
Copy
Edit
npm start
The application will be accessible at http://localhost:3000.

📸 Screenshots


Dashboard displaying project tasks.



Detailed view of a selected task.

📈 Project Structure
bash
Copy
Edit
/backend
  /app
    /models
    /routes
    /utils
  /migrations
  /tests
  .env
  requirements.txt
/frontend
  /public
  /src
    /components
    /redux
    /styles
  package.json
  .gitignore
.gitignore
README.md
🧪 Testing
Backend tests are located in the /backend/tests directory. To run them:

bash
Copy
Edit
pytest
Frontend tests are located in the /frontend/src/tests directory. To run them:

bash
Copy
Edit
npm test
🌍 Contributing
We welcome contributions! To get started:

Fork the repository.

Create a new branch (git checkout -b feature-name).

Make your changes.

Commit your changes (git commit -am 'Add feature').

Push to the branch (git push origin feature-name).

Create a new Pull Request.

📬 Contact
Email: roberta_valyte@hotmail.com

LinkedIn: linkedin.com/in/roberta-valyte

Portfolio: github.com/robertaval


