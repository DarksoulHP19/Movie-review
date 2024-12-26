### Movie-reviewapp

- A movie review app where users can review movies and also add movies to the database.Users can also search for movies and view the reviews of the movies. 

- The app is built using React for the frontend and Node.js for the backend. The database used is MongoDB ,for user verification it uses <b> Mailtrap</b> the images are stored in <b>Cloudinary</b>.
----
### Steps to run the project
- first clone the repository
```bash
$ git clone https://github.com/DarksoulHP19/Movie-review
```

- open the project in your code editor
```bash
$ cd Movie-review
```

- then install the dependencies in the frontend and backend folders

----
### Backend
```bash
$ cd backend
``` 
- install the dependencies
```bash
$ npm install bcrypt cloudinary cors dotenv express express-async-errors express-validator jsonwebtoken mongoose morgan multer nodemailer 
```

- make a .env file in the backend folder and add the following
```bash
JWT_SECRET= "<jwt secret key>"
CLOUD_NAME= "<cloudinary cloud name>"
CLOUD_API_KEY= "<cloudinary api key>"
CLOUD_API_SECRET= "<cloudinary api secret>"

MAIL_TRAP_USER= "< mailtrap username>"
MAIL_TRAP_PASS= "< mailtrap password>"
MONGO_URI =  "mongodb://127.0.0.1:27017/reviewapp"
```

- start the server
```bash
$ npm start
```

----
### Frontend
```bash
$ cd frontend
``` 
- install the dependencies
```bash
$ npm install @testing-library/jest-dom @testing-library/react testing-library/user-event axios react react-dom react-drag-drop-files react-icons react-router-dom react-scripts web-vitals
```

- start the frontend
```bash
$ npm start
```