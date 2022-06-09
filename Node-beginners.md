# Introduction to Node JS for Beginners 
**Node JS** is one of famous frontend and backend language runs on the V8 engine and executes JavaScript code outside a web browser. Node JS is very powerful and easily, it can help us to build simple server quickly, so in many company choose this language as their backend server.

<figure align="center" style="text-align:center;">
  <img
  src="https://i.imgur.com/pBI9kZ5.png"
  width="400px" 
  alt="The beautiful MDN logo.">
    <p>Fig 1.</p>
</figure>


Node JS is **Event driven** that the developer can create scalable server without using threading by using callback to single the completion function. The event driven suit for single thread, so **Node JS is single thread language** that it uses callback function to achieve concurrency. 




Dowload Node: https://nodejs.org/en/download/

Following this command to check node version: 
```bash=
node -v
```

## Package Manger
For Node's package manager, we often use **npm** and **yarn**, it's easier for programmers to publish and share Node packages, and it's designed for simplifying installation, updation, unstinallation. It follows **package.json** to manage whole package in application (Fig 2.).

<figure style="text-align:center;">
  <img
  src="https://i.imgur.com/uSrGiPw.png"
  alt="The beautiful MDN logo.">
    <p >Fig 2.</p>
</figure>



### Npm
**Npm** is default node's package manager. It depend on **package.json** to manage package, then npm generates **package-lock.json** which has the entry of the exact version used by the project after evaluating semantic versioning in package.json.

How to use the NPM ?  We can check npm version, using `npm -v`. The following are useful commands: 
- intial application.
    ```bash=
    npm init -y 
    ```
- install package in global
    ```bash=
    npm install -g <package>@<version>
    ```
- install package in **package.json**
    ``` bash=
    npm install <package>@<version> --save # for dependencies
    npm install <package>@<version> --save-dev # for devDependencies
    ``` 
- uninstall package in **package.json**
    ```bash=
    npm uninstall <package>
    ```
- list all package in **package.json**
    ```bash=
    npm list
    ```
Reference: https://www.npmjs.com/package/yarn

### Yarn
**Yarn** is new Node package manger that focuses on speed, security, and consistency. Yarn is more powerful than **Npm**. Installed library by Npm, it costs lots of time, because Npm downloads package every time. **Yarn caches every package it has downloaded**, so it never needs to download the same package again. After installing package by yarn, it generate **yarn-lock.json** which is same as **package-lock.json**

The following are useful commands: 
- install yarn
    ```bash=
    npm install --global yarn
    ```
- intial application.
    ```bash=
    yarn init -y 
    ```
- install package in global
    ```bash=
    yarn add -g <package>@<version>
    ```
- install package in **package.json**
    ``` bash=
    yarn add <package>@<version>  # for dependencies
    yarn add <package>@<version> --dev # for devDependencies
    ``` 
- uninstall package in **package.json**
    ```bash=
    yarn remove <package>
    ```
- list all package in **package.json**
    ```bash=
    yarn list
    ```
Reference: https://www.npmjs.com/package/yarn

## ES5/ES6
ES means **ECMAScript**

ES6

## babel 

`.babel.rc`


## This 

Arrow function 
## Promise 

## Async

## Typescript 

## Famous Library

### Server 
- http
- express 
- fastify
- koa
- meteor


### Eslint 


