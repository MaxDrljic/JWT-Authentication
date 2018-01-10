Small application made with NodeJS, Express and JSON Web Token. In this app, we are testing routes with POST method by using Postman as a testing platform. Be sure to download Postman if you haven't already.

SETUP :

1. Clone this repo.

2. cd into project.

3. Do `npm install`.

4. Do `npm install nodemon -g` to have your NodeJS server automatically reload after every save.

5. Type `nodemon` in the console to run server.

6. Open Postman and test http://localhost:5000/api/login to generate token. Be sure to copy the value(without the semicolons).

7. In Postman, test another route http://localhost:5000/api/posts and in the Headers section, add `Authorization`, and for the value, add the token value. Click Send. In the Body section, the values should be displayed.