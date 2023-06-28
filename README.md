# BudgetBuddy
BudgetBuddy is an intuitive expense tracking and budget management application built using the MERN stack. It allows users to efficiently track their expenses, categorize them, and visualize their spending habits through interactive graphs and pie charts.

## Features
User Registration and Login: Users can create an account or log in using their credentials.
Expense Management: Users can add, edit, and delete their expenses.
Expense Categorization: Users can categorize their expenses into predefined categories or create custom categories.
Budget Management: Users can set monthly budgets and track their spending against the allocated budget.
Visualization: Users can view their expenses and budget allocations through interactive graphs and pie charts.
Reports: Users can generate reports to analyze their spending patterns over time.
## Technologies Used
MERN Stack:
MongoDB: NoSQL database for storing user information, expenses, and categories.
Express.js: Backend framework for building the server and handling API requests.
React: Frontend library for building the user interface.
Node.js: JavaScript runtime for running server-side code.
Chart.js: JavaScript library for creating interactive charts and graphs.
JWT: JSON Web Tokens for secure user authentication and authorization.
Bcrypt: Library for hashing user passwords.
Bootstrap: CSS framework for responsive and modern UI design.
### Prerequisites
Before running the application, make sure you have the following prerequisites installed on your system:

Node.js (v12 or higher)
MongoDB (v4.4 or higher)
#### Getting Started
Follow these instructions to set up and run the BudgetBuddy application:

Clone the repository:

git clone https://github.com/your-username/budgetbuddy.git
Install the dependencies for the backend server:

cd budgetbuddy/server
npm install
Rename the .env.example file to .env and update the environment variables with your own values:

makefile
PORT=3001
DATABASE_URL=mongodb://localhost:27017/budgetbuddy
JWT_SECRET=your_secret_key
Start the backend server:

cd ../client
Install the dependencies for the frontend:

npm install
Start the frontend development server:

#### Folder Structure
The project structure is organized as follows:

budgetbuddy/
├── server/
│   ├── config/
│   ├── controllers/
│   ├── middleware/
│   ├── models/
│   ├── routes/
│   ├── utils/
│   └── server.js
└── client/
    ├── public/
    └── src/
        ├── components/
        ├── context/
        ├── pages/
        ├── services/
        ├── utils/
        ├── App.js
        ├── index.js
        └── ...
The server folder contains the backend server code, while the client folder contains the frontend code.

##### Acknowledgments
The MERN Stack: MongoDB, Express.js, React, and Node.js.
Chart.js for creating interactive charts and graphs.
Bootstrap for CSS styling and UI components.
JWT and Bcrypt libraries for user authentication and password hashing.
##### Feel free to clone and ask doubt by mail - siddharth.dubey5815@gmail.com
