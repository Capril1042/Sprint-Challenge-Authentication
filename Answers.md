<!-- Answers to the Short Answer Essay Questions go here -->
1. Middleware- is used to connect network based requests  that are generated cilent-side, to the back end data that the cilent is requesting. 
sessions- stores a session identifier on the cilent within a cookie.
bcrypt- is an irreversible  password hashing function that is used to encrypt passwords
JWT- Stands for JSON Web Token, a JSON web token is used for authenication. Once a user is signed in, requests made use this token allowing the user to access the routes permitted by that token. This way the user doesnt have to constantly sign in with their password to access these routes.
2. In order to prevent attacks, bcrypt uses a salt to prevent rainbow table attacks, the number of salt rounds can be increased, so as ways to  decode get faster and better, so can the encrytion level. bcrypt is also an example of one way hashing, once the password is hashed that function is irreversible.
3. The three parts of the JSON web token are; header, payload and signature
