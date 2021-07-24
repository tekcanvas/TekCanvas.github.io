---
layout: post
title:  "Understanding react components and props"
author: arkit
categories: [ ReactJs ]
image: assets/images/react-hello.jpeg
---
This tutorial requires prior knowledge of JavaScript and ReactJs.

Now we have created our first React App lets deep dive into some react concepts for Components and props.

## Components and Props

Components lets you modularize your UI into independent & reusable elements.You can put your HTML elements you want to render in separate functions and later use these as independent components.

There are mainly two types of componets:

* **Function components or stateless components**
* **Class components or stateful components**

### React JS Function Components or Stateless components

Functional components are nothing but are simple Javascript functions that are programmed to return JSX value.

Let's creates a simple functional component

~~~JSX
function ComponentName(props) {
  return <h1>Print value of count from props, {props.count}</h1>;
}
~~~

A functional compont can also be created using lambda or arrow function

~~~JSX
const ComponentName = (props) => { 
  return <h1>Print value of count from props, {props.count}</h1>; 
}
~~~

React JS component takes input called props. So if we need to pass to component then we will use React js props to pass it to the component.

In the above example we have passed a variable named **count** and used that count to show it in html tag.

## React JS Class Components or Stateful components

React Class components are E6 class which extends React.Component. The component's name must start with an upper case letter. Class components are called stateful components as they have access to the react state instance variable that holds all the variables of a component over the lifetime.

Let's creates a simple class component

~~~JSX
class ClassComponent extends React.Component{
    constructor(props){
        super(props);
    }
    render(){
        return (
            <div><h1>Print value of count from props, {props.count}</h1></div>
        )
    }
}
export default ClassComponent;
~~~

### Steps to convert function component to class component

* Create an ES 6 class with same name as function component and extends React.Component.
* Copy the function body in the render method.
* Replace props with this.props in all appearance.

## Props

Props are immutable i.e you cannot change the value of props.For example if you want to change the value props then you cannot.


So now you have gained some knowledge about components and props lets move onto next topic 

