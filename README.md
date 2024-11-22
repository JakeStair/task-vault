# Task Vault

Task Vault is a Kanban board application enhanced with authentication using JSON Web Tokens (JWT). This project demonstrates secure and scalable authentication for full-stack applications, ensuring user identity verification and secure API interactions. 

The core functionality includes user login, token-based authentication, and a deployed Kanban board application accessible via a live URL.

## Table of Contents

- [Features](#features)
- [Installation](#installation)
- [Usage](#usage)
- [Deployment](#deployment)
- [License](#license)

---

## Features

- **JWT Authentication**: Secure login and token-based user authentication.
- **Kanban Board**: User-friendly interface for managing tasks.
- **RESTful API**: Authenticated routes for tickets and users.
- **Token Storage**: Secure token handling with localStorage.
- **Environment Configuration**: Customizable `.env` file for secure application setup.

---

## Installation

1. **Set up the server**:
   - Navigate to the `server` directory.
   - Create a `.env` file with the following variables:
     ```plaintext
     DB_USERNAME=<your_database_username>
     DB_PASSWORD=<your_database_password>
     JWT_SECRET=<your_secret_key>
     ```

2. **Install dependencies for both server and client**:
   ```bash
   cd server
   npm install
   cd ../client
   npm install


### Start the Development Servers

- **Server**:  
  Navigate to the `server` directory and run:  
  ```bash
  cd server
  npm run dev

- **Client**: 
  ```bash
  cd client
  npm start

## Usage

1. Open the application in your browser.
2. Navigate to the login page and authenticate with valid credentials.
3. Access the Kanban board to view, manage, and track tasks.
4. Test the server API directly using Insomnia or similar tools.

## Deployment

The application is deployed on [Render](https://render.com).

- **Live Application URL**: [Task Vault Live](<>)
- **GitHub Repository**: [Task Vault GitHub](<https://github.com/JakeStair/task-vault>)

Refer to the [Render Documentation](https://render.com/docs) for guidance on setting environment variables and deployment.
