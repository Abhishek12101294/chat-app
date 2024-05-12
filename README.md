# Chat Application 
Chat application build with the power of MERN Stack.

## Installation Guide

### Requirements
- [Nodejs](https://nodejs.org/en/download)
- [Mongodb](https://www.mongodb.com/docs/manual/administration/install-community/)

Both should be installed and make sure mongodb is running.
### Installation

```shell
git clone https://github.com/Abhishek12101294/chat-app.git
```
Now rename env files from .env.example to .env
```shell
mv .env.example .env
```

Now install the dependencies
```shell
yarn
```
We are almost done, Now just start the development server.

Open another terminal in folder, Also make sure mongodb is running in background.
```shell
cd server
yarn start
```
Done! Now server is running on localhost:3000