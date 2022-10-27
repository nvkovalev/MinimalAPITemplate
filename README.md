# Clean Minimal API with FastEndpoints
Template API project using FastEndpoints 

# Examples

### Get all users
GET https://localhost:5001/customers
Accept: application/json

### Get user by id
GET https://localhost:5001/customers/id
Accept: application/json

### Create customer
POST https://localhost:5001/customers
Content-Type: application/json

{
  "username": "Logan",
  "fullName": "Logan Blackburn",
  "email": "logan_blackburn@mail.com",
  "dateOfBirth": "2000-01-17"
}

### Update customer
PUT https://localhost:5001/customers/
Content-Type: application/json

{
  "username": "Logan",
  "fullName": "Logan Blackburn",
  "email": "logan_blackburn@mail.com",
  "dateOfBirth": "2000-01-17"
}

### Delete user
DELETE https://localhost:5001/customers/id
Accept: application/json

