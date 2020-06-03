# Authentication-Practice
A secret-sharing website built to practice authentication using Oauth and local strategies via passport.js. This project was built using node with express, EJS and mongoose. 

Link to website : https://infinite-gorge-72798.herokuapp.com/

go to link above and navigate to /secrets to see all the secrets that have been entered. Submitting a secret requires you to register, or log in. A session is created after logging in which persists until the browser remains open.So the user need only log in once.

ISSUE: duplication of null "email" field crashes the app upon multiple users using Google to sign up. The email/username field can be left null only once, hence the error.
