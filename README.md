# Carelyo LIA Test
## Question 1
Have not used long polling before
## Question 2
Cookies have an expirey time, localstorage do not. Cookies are used for storing client to server data whereas localstorage is used mostly for settings preferences etc. Localstorage is only stored within the browser/operating system
## Question 3
GET - retrieves data 
PUT - creates/replaces a resource 
DELETE - Deletes specified resource
POST - Sends data to server from client
## Question 4
An array is a list of data stored within a specified sequence, we can access a specified item within a list by using indexing. We can store strings, integers, floats and boolean data within an array. Within javascript/typescript an object has a type and properties and is mostly used to describe things that contain different types of information with properties.
## Question 5
A javascript/typescript framework
**A.** We use react hooks to manage states without the need for classes. Hooks are fundamentally javascript functions.

**B.**
***Don’t call Hooks inside loops, conditions, or nested functions.*** If we don't avoid this we risk not getting the same order each time a component renders. ***Don’t call Hooks from regular JavaScript functions.*** If we call hooks from regular Javascript functions we cannot be sure that all stateful logic in a component is clearly visible from its source code. ***Only call hooks at the top level***. Same as the first rule, hooks should only be called at the top level of your functional component, not inside loops, conditions, or nested functions.

**C.** JSX stands for javascript xml and is the preferred file format to write react in. There's also tsx for typescript language. We use these formats to add html to React. 

**D.** Global variables that can be used with React. This functionality is provided by NodeJS. I have used this for passwords, urls and such that I don't want to share publicly with Github.

**E.** Arguments in React components.

**F.** With useState function. Example: const [state, setState] = useState(“on”)

**G.** No, only one with vanilla React.

**H.** Using components in order to achieve better speed, scalability, and standardization. We use components for things the site might not need to call all the time, in that way the website is dynamic.

**I.**

1.  
```
import React from 'react';
function LoginButton(props) {
  return (
    <button onClick={props.onClick}>
      Click to login
    </button>
  );
}
export default LoginButton;

import React, { useState } from 'react'; 
import LoginButton from './Components/LoginButton';
function LoginFunction() {
  const [isLoggedIn, setIsLoggedIn] = useState(false);
  function handleLoginClick() {
    setIsLoggedIn(true);
  }
  return (
    <div>
      {isLoggedIn ? (
        <p>You are logged in</p>
      ) : (
        <LoginButton onClick={handleLoginClick} />
      )}
    </div>
  );
}
```
## Question 6
![image](https://user-images.githubusercontent.com/90619276/214799990-ec71f230-1996-4cdc-9f87-07fbbdd1222a.png)
![image](https://user-images.githubusercontent.com/90619276/214800153-e54154f0-b628-40ac-be22-5a917e1e7a95.png)
![image](https://user-images.githubusercontent.com/90619276/214800298-c1569fac-33aa-473a-a7d3-2d8038924870.png)
## Question 7
Typescript is a typed language built on top of Javascript.
**A.** We can define types and also check types in inputs etc.

**B.** Easier to debug code but more time consuming to write.

**C.**
```
{/* JS */}
let var1 = 12
let var2 = var1+2
console.log(var2)
{/* TS */}
let var1: number = 12
let var2: number = var1+2
console.log(var2)
```
## Question 8
A userstory is a request from a user perspective.
**A.**
As a user of Shopify I want my basket to remember what's inside from last visit.

**C.**
Agile sprints, testing of new design, user input, ux development and can also be used as requirements for mvp/end project.

## Question 9
Git is a version control system
**A.** Scripts that run automatically every time a particular event occurs in a Git repository.

**B.** A specification for adding human and machine-readable meaning to commit messages.

**C.** 
```
feat: Created component to navbar component.
The component shows up only when a user is logged and shows time left before the current session ends
```

## Question 10
Accessability is when you optimize your website for people with different disabilities like colorblindess.
**A.** You ensure the customer no matter what condition they're having can read and interact with the website like everyone else.
**B.** Color, contrast, size, font style (dyslexia) etc etc

## Question 11
More about React, how to work in a team on Github, how to maintain a website/online service, how a development team work, how online businesses operate.
