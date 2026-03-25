
### Requirements
- [Nodejs](https://nodejs.org/en/download)
- [Mongodb](https://www.mongodb.com/docs/manual/administration/install-community/)

Both should be installed and make sure mongodb is running.
### Installation

#### First Method
```shell
cd chat-app-react-nodejs
```
Now rename env files from .env.example to .env
```shell
cd public

cd ..
cd server

cd ..
```

Now install the dependencies
```shell
cd server
npm install
cd ..
cd public
npm install
```
We are almost done, Now just start the development server.

For Frontend.
```shell
cd public
npm start
```
For Backend.

Open another terminal in folder, Also make sure mongodb is running in background.
```shell
cd server
npm start
```
Done! Now open localhost:3000 in your browser.
HEAD
=======
