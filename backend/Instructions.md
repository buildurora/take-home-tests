# Backend Take-home Exercise

```
TIMEBOX:    2-3 hours (recommended)
LANGUAGES:  Typescript, Golang, Python or C#

```

## Overview

This exercise is mean to test your ability to build a simple statefull application, that exposes and API.

It could be a REST API, GraphQL, or any other API that you are comfortable with.

The things we are looking at are included in the list below. We are not looking for a perfect solution, but we are looking for a solution that is well thought out and shows your ability to take a design and turn it into a working application.

```

1. The implemented solution matches requirements
2. The code is well structured and easy to read
3. The code is well tested
4. The code is well documented
5. Linting & Formatting tools
6. Database migrations

```

## Prompt

### Database Design

We need to store information about our users and their accounts.

You can choose from POSTGRES, MySQL, or SQLite for this exercise.

We need to store the following information:

- User

  - User ID
  - First Name
  - Last Name
  - Email
  - Phone Number
  - Date of Birth
  - Address
  - Account
    - Account Number
    - Account Type
    - Account Balance
    - Account Status
    - Account Created Date

- Transaction
  - Transaction ID
  - Account Number From
  - Account Number To
  - Transaction Date
  - Transaction Amount
  - Transaction Type
  - Transaction Status
  - Transaction Description

### API Design

We need to expose the following API endpoints:

- Login (For this exercise assume users already exist)
- Create User
- Get User
- Get transactions by User ID
- Update User
- Delete User
- Create Account
- Get Account
- Update Account
- Delete Account
- Create Transaction
- Get Transaction

## Submitting your exercise

```
1. Please create a private repo on Github and add the following users as collaborators:
2. Include a README.md file with instructions on how to run your application
3. Maintain a commit history that shows your progress

```

### Bonus points

1. Transactions should be immutable. Once a transaction is created, it should not be updated.
2. Deploy your application to a free tier cloud provider.
3. Setup a CI/CD pipeline to automatically deploy your application to a free tier cloud provider.
4. Add a feature that is not in the requirements
