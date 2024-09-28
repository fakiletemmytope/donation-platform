# Donation Platform-Project

---

Donation app is a web platform that allows a registered user to solicit for fund for a cause/project and hence serves as a medium where donors can donate towards a cause. The platform has a payment gateway integrated where all donations are accepted before passing it to the fund solicitor

## Technology Stack

- Nodejs for building
- Exprress Framework
- MongoDB
- Authentication (OAuth2/JWT for secure access)

### Features

- Users Authentication
- Causes
- Donations
- Paystack payment integration

### Endpoints (Folder: 'router/courses')

- Users:
  - GET /users/: Retrieve a list of users.
  - GET /users/{user_id}/: Retrieve details of a specific user.
  - POST /users/: Create a new user.
  - PUT /users/{user_id}/: Update an existing user.
  - DELETE /users/{user_id}/: Delete a user.
  - POST /
- Causes:
  - GET /causes/: Retrieve a list of causes.
  - GET /causes/{cause_id}/: Retrieve details of a specific cause.
  - POST /causes/: Create a new cause.
  - PUT /causes/{cause_id}/: Update an existing cause.
  - DELETE /causes/{cause_id}/: Delete a cause.
- Donation:
  - GET /donations/: Retrieve a list of donations.
  - GET /donations/{donation_id}/: Retrieve details of a specific cause.
  - POST /donations/: make donations.
  - GET /donations/user/:user_id: Retrieve all the donations made by a specific user
  - GET /doantions/donation-reference/:reference: for verification of payment towards a cause.

### HOSTED LINK

[Donation-platform](https://donation-platform-be.onrender.com/users)
