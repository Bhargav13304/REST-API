REST API
A lightweight RESTful API built with Node.js and Express.js, designed to handle basic CRUD operations. This project serves as a foundational example for understanding REST principles and API development.

🛠️ Tech Stack
Backend: Node.js, Express.js

Templating: EJS

Styling: CSS

Runtime: JavaScript

🚀 How to Run the Project
Clone the repository:

bash
Copy
Edit
git clone https://github.com/Bhargav13304/REST-API.git
cd REST-API
Install dependencies:

bash
Copy
Edit
npm install
Start the server:

bash
Copy
Edit
node solution.js
Access the application:

Open your browser and navigate to http://localhost:3000

✨ Features
Create new entries

Read existing entries

Update entries

Delete entries

Dynamic content rendering with EJS templates

🧪 How to Use the API
This application is primarily a web-based interface, but you can simulate interactions using tools like Postman for testing routes.

Endpoints
GET / - Home page

GET /submit - Form to submit data

POST /submit - Submit data (use Postman or form submission)

GET /entries - View all submitted entries

Using Postman
Launch Postman

Use POST method for http://localhost:3000/submit

Set the body type to x-www-form-urlencoded

Add key-value pair: entry: your data

Send the request and check output at http://localhost:3000/entries

📁 Folder Structure
graphql
Copy
Edit
REST-API/
├── public/
│   └── styles/          # CSS files for styling
├── views/               # EJS templates for rendering pages
├── solution.js          # Main server file
├── package.json         # Project metadata and dependencies
└── README.md            # Project documentation
