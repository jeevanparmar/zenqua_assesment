# Express.js CRUD API

A simple CRUD (Create, Read, Update, Delete) REST API built using Express.js, MongoDB, and Mongoose.

## Features

* Create a new user
* Get all users
* Get a user by ID
* Update user details
* Delete a user
* MongoDB database integration

## Tech Stack

* Node.js
* Express.js
* MongoDB
* Mongoose

## Installation

1. Clone the repository

```bash
git clone <repository-url>
cd <project-folder>
```

2. Install dependencies

```bash
npm install
```

3. Start the server

```bash
npm run dev
```

## API Endpoints

### Create User

```http
POST /api/users
```

### Get All Users

```http
GET /api/users
```

### Get User By ID

```http
GET /api/users/:id
```

### Update User

```http
PUT /api/users/:id
```

### Delete User

```http
DELETE /api/users/:id
```

## Sample Request Body

```json
{
  "name": "Jeevan",
  "email": "jeevan@gmail.com"
}
```

## Author

Jeevan Parmar
