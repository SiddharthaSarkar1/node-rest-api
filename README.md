# Node REST API

# In this project I have build a REST API using Node, Express, TypeScript & MongoDB + Authentication

I have built a REST API with Node.js, Express and TypeScript. We have used MongoDB as our Database.

A beginner friendly easy to learn project.


* Some Important notes are given below.

> npm init -y
****[Using npm init --yes to Instantly Initialize a Project
If you want to get on to building your project and don't want to spend the (albeit brief) time answering the prompts that come from npm init , you can use the --yes (or -y ) flag on the npm init command to populate all options with the default values automatically]

We need to install TypeScript : 
> npm install -D typescript

We need to install ts-node : 
> npm install -D ts-node

We will install nodemon:
> npm install -D nodemon

Now we will create a new file tsconfig.json where we will configure Typescript
{
    "compilerOptions": {
        "module": "NodeNext",
        "moduleResolution": "node",
        "baseUrl": "src",
        "outDir": "dist",
        "sourceMap": true,
        "noImplicitAny": true,
    },
    "include": ["src/**/*"]
}

Now we will create a new file nodemon.json where we will configure nodemon
{
    "watch": ["src"],
    "ext": ".ts,.js",
    "exec": "ts-node ./src/index.ts"
}

Now, create a folder src and create a file index.ts inside that

Now in package.js add a script "start": "nodemon",

"scripts": {
    "start": "nodemon",
    "test": "echo \"Error: no test specified\" && exit 1"
  }

Now run the project
> npm start

> npm i express body-parser cookie-parser compression cors http

> npm i -D @types/express @types/body-parser @types/cookie-parser@types/compression @types/cors

Here we have done the MongoDB Atlas setup 

> npm install mongoose

> npm i -D @types/mongoose

-------------------------------------------------------------

http://localhost:8080/auth/register

{
  "email ": "siddharthas@mail.com",
  "password" : "12345",
  "username" : "codersidd"
}

"email": "siddharthas@mail.com",
  "password": "12345"

> npm install lodash

> npm i -D @types/lodash













































