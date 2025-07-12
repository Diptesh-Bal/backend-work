# Backend Work

This project is a Node.js backend API built with Express and TypeScript. It demonstrates user authentication, user management, and secure REST API practices using MongoDB as the database.

## Features

- **User Registration & Login:** Secure authentication with hashed passwords and session tokens.
- **User Management:** Get all users, update user info, and delete users (with authentication and authorization).
- **Middleware:** Includes authentication and ownership checks for protected routes.
- **Modular Structure:** Organized controllers, routes, middlewares, and helpers for scalability.
---

## Tech Stack

- **Node.js** & **Express** for the server
- **TypeScript** for type safety
- **MongoDB** with **Mongoose** for data storage
- **Lodash** for utility functions

---

## Project Structure

```
backend-work/
│
├── src/
│   ├── controllers/    # Route handlers
│   ├── db/             # Database models and queries
│   ├── helpers/        # Utility functions (e.g., authentication)
│   ├── middlewares/    # Express middlewares (auth, ownership)
│   ├── router/         # Route definitions
│   └── index.ts        # App entry point
│
├── package.json        # Project dependencies and scripts
├── tsconfig.json       # TypeScript config
└── README.md           # Project documentation
```
---

## Getting Started

### Prerequisites

- Node.js (v16+ recommended)
- MongoDB database (local or Atlas)

### Installation

1. Clone the repository:
   ```sh
   git clone <repo-url>
   cd backend-work
   ```
2. Install dependencies:
   ```sh
   npm install
   ```
3. Set up environment variables:
   - Copy `.env.example` to `.env` and update the values as needed.
4. Run the development server:
   ```sh
   npm run dev
   ```
5. Access the API documentation:
   - Navigate to `http://localhost:3000/api-docs` in your browser.

---

## Usage

- Use tools like Postman or Insomnia for API testing.
- Register a new user, then log in to access protected routes.
- Explore the API documentation for available endpoints and their usage.

---

## Contributing

1. Fork the repository
2. Create a new branch: `git checkout -b feature/YourFeature`
3. Make your changes
4. Commit your changes: `git commit -m 'Add some feature'`
5. Push to the branch: `git push origin feature/YourFeature`
6. Submit a pull request
