# Contact Management API

A RESTful API for managing contacts using Node.js, Express, MongoDB, and Mongoose.

## Table of Contents

- [Features](#features)
- [Technologies Used](#technologies-used)
 - [Environment Variables](#environment-variables)
  - [API Endpoints](#api-endpoints)


## Features

- Create a new contact
- Retrieve all contacts
- Retrieve a single contact by ID
- Update a contact
- Delete a contact

## Technologies Used

- Node.js
- Express
- MongoDB
- Mongoose
## API Endpoints
The following endpoints are available:

GET /api/contacts - Retrieve all contacts
POST /api/contacts - Create a new contact
Required fields: name, email, phone
GET /api/contacts/
- Retrieve a contact by ID
PUT /api/contacts/
- Update a contact by ID
DELETE /api/contacts/
- Delete a contact by ID


## Example
Example usage:

# Create a new contact:

POST /api/contacts
{
  "name": "John Doe",
  "email": "john.doe@example.com",
  "phone": "123-456-7890"
}

# Retrieve all contacts:

GET /api/contacts

# Retrieve a contact by ID:

GET /api/contacts/:id


# Update a contact by ID:

PUT /api/contacts/:id
{
  "name": "Updated Name",
  "email": "updated.email@example.com",
  "phone": "987-654-3210"
}
# Delete a contact by ID:
DELETE /api/contacts/:id
