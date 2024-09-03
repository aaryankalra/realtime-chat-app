# crapchat
crapchat is a real-time chat application project created using the MERN stack. it is a basic yet good looking real-time platform that allows users to chat and connect with users around the world. this project uses modern web technology to provide seamless real-time messages, user authentication and dynamic user interface.

## features of the project:
1. user authentication (using jwt tokens)
2. dynamic profile picture 
3. real-time messaging (using socket.io)
4. notification sounds
5. encrypted passwords (using bcryptjs)
6. searching and filtering

## tech stack used in the project:
1. MongoDB
2. ExpressJS
3. ReactJS
4. NodeJS
5. Socket.io

## other technology used in the project:
1. DaisyUI
2. react-icons
3. react-hot-toast

## steps to run the project:
### step 1: install node packages in the root folder
```
npm i
```
### step 2: install node packages in the frontend folder
```
cd frontend
npm i
```
### step 3: set up your .env file
create a .env file in the root folder and adjust it's content based on:
```
PORT =
MONGO_DB_URI =
JWT_SECRET =
NODE_ENV =
```
### step 4: run the server
run the following command in the root folder to start the MongoDB server
```
npm run server
```
### step 5: start the frontend
```
cd frontend
npm run dev
```

## future scope of the project:
1. sending/receiving images and videos
2. custom profile picture
3. group channels
