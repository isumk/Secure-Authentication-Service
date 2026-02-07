# Secure-Authentication-Service
Standalone authentication and authorization service implementing JWT, role-based access control, and security best practices.

## Overview
This project is a standalone authentication and authorization service built with a strong focus on security best practices.

It can be integrated into any web or mobile application requiring secure user authentication.

## Features
- User registration and login
- Password hashing using bcrypt / argon2
- JWT access and refresh tokens
- Role-based authorization
- Rate limiting and brute-force protection
- Account lockout on multiple failed attempts

## Technology Stack
- Node.js
- Express.js
- PostgreSQL
- JWT
- Helmet
- Swagger for API documentation

## API Design
The API follows RESTful design principles and includes versioning.

- `/api/v1/auth/register`
- `/api/v1/auth/login`
- `/api/v1/auth/refresh`
- `/api/v1/users`

## Security Practices Implemented
- Secure password storage
- Token expiration and rotation
- Input validation
- Secure HTTP headers
- Logging and monitoring

## Testing
- Unit tests for authentication logic
- Integration tests for API endpoints

## How to Run
1. Configure `.env`
2. Run database migrations
3. Start the server using `npm start`

## Use Cases
- Authentication microservice
- Backend security demonstration
- Learning reference for secure systems

## Author
Isum Kariyawasam
