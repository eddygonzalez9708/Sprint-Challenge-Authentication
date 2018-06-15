<!-- Answers to the Short Answer Essay Questions go here -->

1. Describe Middleware, Sessions (as we know them in express), bcrypt and JWT.

    Middleware is a function that is executed before another middleware function or promise is executed. As a result, middleware allows developers to offload work in their express applications.

    A session is a period in time in which two or more computers communicate with each other and exchange information. In addition, a session may be terminated by an expiration date or when one of the computers involved in the communication link leave the session. 

2. What does bcrypt do in order to prevent attacks?

    bycrypt is a hashing algorithm used for password encryption that protects passwords from brute-force and rainbow table attacks. It is able to protect passwords by taking extra parameters to its algorithm, such as the cost. The cost parameter is the amount of time between each hashing attempt. Therefore, the cost can slow down the hacking process because if the cost parameter is increased it could potentially take minutes, days, months, or even years to un-hash an encrypted password.

3. What are the three parts of the JSON Web Token?

    The three parts of the JSON Web Token includes the header, payload and signature.
