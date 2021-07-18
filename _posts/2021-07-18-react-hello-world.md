---
layout: post
title:  "React Hello World"
author: arkit
categories: [ ReactJs ]
image: assets/images/react-hello.jpeg
keywords:
  - react
  - hello world
  - beginner
  - rookie
  - react developer
  - react development
  - learn react
  - first react programming

---
Today I will explain how to create the hello world app in react js.

This tutorial requires a basic knowledge on javascript. No prior knowledge on react js is required.

## Introduction

### What is React? 

[React.js](https://reactjs.org/) a javascript library for building user interfaces, being developed by Facebook Engineers and then it was later open-sourced in 2013. 

## Getting Started: Create React App

**create-react-app** is a command to create React App with default configuration. This will enable us to start writing code immediately. 

Check out the documentation [here](https://create-react-app.dev/) if you have any questions or want to dive in a touch deeper on how the tool works.

Now install create-react-app globally with command on your computer's terminal using the below command:

~~~bash
npm install –g create-react-app
~~~

Now create a react application with default configuration with name of your choice, here we are naming our app **react-hello-world**

~~~bash
npx create-react-app react-hello-world
~~~

Start the app to check how the initial set looks like, to start navigate to the application directory and run start command.

~~~bash
cd react-hello-world
npm start
~~~

Now you have started the app successfully, open the browser and type the URL [localhost:3000](http://localhost:3000/). Your browser will display something like this

![React Default Startup Page](/assets/images/post/react/react-default-startup-page.png)