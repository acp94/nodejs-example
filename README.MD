Comment for package.json file
1. Express is the framework.
2. Ejs is the templating engine.
3. Mongoose is object modeling for our MongoDB database.
4. Passport stuff will help us authenticating with different messages.
5. connect-flash allows for passing session flashdata messages.
6. bcrypt-nodejs gives us the ability to hash the password.

ExpressJS 4.0 dependencies (morgan, body-parser, cookie-parser, method-override, express-session)


Server.js is application setup


Database config config/database.js


Routes app/routes.js
We will keep our routes simple for now. We will have the following routes:
1. Home page (/)
2. Login page (/login)
3. Signup page (/signup)
4. Handle the POST for both login
5. Handle the POST for both signup
6. Profile page (after logged in)
