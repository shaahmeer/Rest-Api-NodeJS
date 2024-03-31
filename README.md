CRUD REST API built with Node.js, Express, and PostgreSQL,  information about the project, how to set it up, and how to use the API. 

---

# CRUD REST API with Node.js, Express, and PostgreSQL

This is a simple CRUD (Create, Read, Update, Delete) REST API built using Node.js, Express framework, and PostgreSQL database. The API provides endpoints to perform CRUD operations on a 'users' table in the PostgreSQL database.

## Setup Instructions

1. Clone the repository:
   ```bash
   git clone <repository_url>
   ```

2. Install dependencies:
   ```bash
   npm install
   ```

3. Set up PostgreSQL database:
   - Create a PostgreSQL database and update the connection details in `connection.js`.

4. Start the server:
   ```bash
   node api.js
   ```

## API Endpoints

### Get All Users
- Endpoint: `GET /users`
- Description: Retrieves all users from the database.

### Get User by ID
- Endpoint: `GET /users/:id`
- Description: Retrieves a user by their ID from the database.

### Add User
- Endpoint: `POST /users`
- Description: Adds a new user to the database.

### Update User
- Endpoint: `PUT /users/:id`
- Description: Updates an existing user in the database.

### Delete User
- Endpoint: `DELETE /users/:id`
- Description: Deletes a user from the database by their ID.

## Usage

1. Make requests to the API using tools like Postman or cURL.
2. Ensure to include appropriate data in the request body for POST and PUT requests.

---

You can customize this template further based on additional details you want to include about your project. Save this content in a file named `README.md` in the root directory of your project.
