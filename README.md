Welcome to the Blog Project repository! This project is a modern blogging platform built with a variety of technologies. Below you will find information on how to set up, use, and contribute to the project.

- Table of Contents
- Project Overview
- Technologies Used
- Installation
- Usage
- Common Package
- Deployment
- Contributing
- License
- Project Overview
  
  This project is a full-stack blogging platform with a React frontend and a TypeScript backend. It supports features like Signup, SignIn, posting blogs, Getting all the blogs, Once any blog is clicked getting details about particular blog
 and user management. The backend is deployed on Cloudflare Workers, and the project also includes a common package published to npm for shared functionalities.

**Technologies Used**
**Frontend**
React: A popular library for building user interfaces.
Hooks: For managing state and side effects in React.
TypeScript: For static type checking and improved development experience.

**Backend**
Prisma: An ORM for interacting with the database.
TypeScript: For type safety and better development tooling.
Hono: A lightweight framework for building APIs.
PostgreSQL: The database used for storing blog data.
**Common Package**
A shared npm package used across both frontend and backend for common utilities and types.
Installation
Frontend
Clone the repository:

bash
Copy code
git clone https://github.com/jkratee/blog-app.git
cd blog-project/frontend
Install dependencies:

bash
Copy code
npm install
Start the development server:

bash
Copy code
npm start
Backend
Clone the repository:

bash
Copy code
git clone https://github.com/jkratee/blog-app.git
cd blog-project/backend
Install dependencies:

bash
Copy code
npm install
Set up environment variables:

Create a .env file based on the .env.example provided.
Start the server:

bash
Copy code
npm start
Usage
After setting up both frontend and backend, navigate to http://localhost:3000 to access the application.

Common Package
To use the common package in your project, install it via npm:

bash
Copy code
npm install @jkratee/common-package
Import and use the utilities as needed in your code.

Deployment
Backend
The backend is deployed on Cloudflare Workers. For details on deployment, refer to the Cloudflare Workers documentation.

Frontend
You can deploy the frontend using your preferred hosting service (e.g., Vercel, Netlify). Follow the respective documentation for deployment instructions.

Contributing
We welcome contributions to the project! Please follow these steps to contribute:

Fork the repository.
Create a new branch (git checkout -b feature-branch).
Make your changes.
Commit your changes (git commit -am 'Add new feature').
Push to the branch (git push origin feature-branch).
Create a new Pull Request.
License
This project is licensed under the MIT License - see the LICENSE file for details.
