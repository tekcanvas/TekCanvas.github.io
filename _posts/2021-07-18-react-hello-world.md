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
This tutorial will give you a basic understanding of React by building a very  simple application so let's start creating your first React App for Hello World!.

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


Now open the project in your favourite IDE, here we are using visual studio code.

![React Hello World Initial Project Structure](/assets/images/post/react/react-hello-world-initial-setup.png)

Now let’s create a simple Hello World! application with this project.

Now navigate to src folder and open index.js and replace the content with the below code snippet.

~~~JSX
import React from 'react';
import ReactDOM from 'react-dom';

ReactDOM.render(
  <div> <h1> Hello World ! </h1></div>,
  document.getElementById('root')
);
~~~

![React Hello World Browser View](/assets/images/post/react/react-hello-world-first-render.png)

### Functional Components

Components lets you modularize your UI into independent & reusable elements.You can put your HTML elements you want to render in separate functions and later use these as independent components.

A simple functional component may look like

~~~JSX

function ComponentName() {
     return( 
      <html-component> </html-component>
   )
}
ReactDOM.render(<ComponentName/> , document.getElementById('root'))

~~~

Now let's write the Hello World! using functional components

![React Hello World Functional Component](/assets/images/post/react/react-hello-world-functional-componet.png)

Now lets link it to **index.js**
 
![React Hello World Functional Component Index Page](/assets/images/post/react/react-hello-world-functional-componet-indexpage.png)

Now lets view it in browser

![React Hello World Browser View](/assets/images/post/react/react-hello-world-first-render.png)

Now you have created your very first React App lets learn some core concepts of React on the next tutorial.
