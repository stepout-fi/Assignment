# Stepout Backend Intern Assignment

You will have 10 days to complete your assignment. Please notify us when you are done with the tasks. Send an email to trung@stepout.fi when you are done or if you have any questions. Happy coding and good luck!

## Installation and Setup


```bash
# Install dependencies for server
npm install

# Run the application
npm run start

# Server runs on http://localhost:3000 
```

## Assignment Instruction

* The solution should be made within this expressJS application.
* You can clone or fork the project. 
* You are free to structure your Express JS application on how you like.
* Your api route must be `api/<feature-name>`.

## Task


1. Implementation of Google Oauth and Authentication with a database of your choice.

    *   Implement a Google Oauth login .
    *   Implement a Authentication route to login/register user.
    *   Implement a fake authorized api route `api/users` where you can see all registered user. In this route, it should check for **Header Authorization:** `Bearer FAKE_TOKEN` string.

2. Implementation of a simple subscription from Stripe.

    *   Implement a simple subscription model that a user could subscribe to only after they are logged in to the application.
    *   The subscription period should be 30 days.
    *   Create an API route `api/user/<user-id>/subscription` for logged-in user to see their own subscription information. 


## Tip

* Stepout team loves clean code and would love to see your consideration on readability and performance.
* We love good test case if possible.
* We love to learn about your development through a README