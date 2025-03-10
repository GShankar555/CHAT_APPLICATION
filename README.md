The Chat Application project using the MERN (MongoDB, Express.js, React, Node.js) stack
is designed to provide users with a real-time messaging platform. The application allows users
to register, create chat rooms, and exchange messages with other users in real-time. It utilizes
web sockets for real-time communication and stores chat history in a MongoDB database. The front-end of the application is built using React, which provides a responsive and interactive
user interface. Users can create accounts, log in, and join different chat rooms. The back-end
is powered by Node.js and Express.js, which handle user authentication, message routing, and
database operations. Key Features:
1. User Authentication: Users can register, log in, and log out securely.
2. Real-time Messaging: Users can exchange messages with other users in real-time.
3. Chat History: Messages are stored in a MongoDB database, allowing users to view past
conversations.
4. Responsive Design: The application is designed to work seamlessly on desktop and mobile
devices.

![login page](./images/snappy_login.png)

![home page](./images/snappy.png)

## Installation Guide

```shell
git clone https://github.com/GShankar555/CHAT_APPLICATION
cd chat-app
```
Now install the dependencies
```shell
cd server
yarn
cd ..
cd public
yarn
```
We are almost done, Now just start the development server.

For Frontend.
```shell
cd public
yarn start
```
For Backend.

Open another terminal in folder, Also make sure mongodb is running in background.
```shell
cd server
yarn start
```
