# Learning-React

WHAT ?

React is an open-source JS library for building user interface. It is not a framework but a library, it foucses on rich UI. 
It has a rich ecosystem, plays well with other libraries.



WHY ?

 - Facebook uses React, invests a lot, thus a huge community.
 - In demand skillset

 - Component Based Architecture( Lets you break down into small encapsulated parts)
 - Makes it possible to write usable code.
 - React is declarative ( tell React what you want and React will build the UI), inplace of the imperative paradigm. Thus, react abstracts the process of building a UI.
 - Seemless integration with other applications.
 - React Native for mobiles

 FLOW 

 - Fundamentals
 - HTTP
 - ROuting
 - Redux
 - Utilities

 Creating a React App

 1. 
 - npx create-react-app <project_name>

 - npx is a npm package runner, which gets installed when we install node. 

 2. 

 npm install create-react-app -g ( install it globally)
 create react-app <project_name>

 ## Understanding the file structure of a React App

 1. package.json   // contains dependencies and scripts required for the project.
 2. package-lock.json // npm as package manager
 3. gitignore
 4. readme.md

 //folders

 5. node_modules - all the dependencies are installed

 6. public folder
    ---- manifest.json
    ---- index.html // only html file, typically no code changes here. 1 div tag with id = "root"
    ---- favicon.ico
7. src folder
    ---- index.js //starting point for our application - we specify the root component or the app component and the DOM element which will be controlled by React.( div id ="root")
    ---- app.js // responsible for the html displayed in the browser, controls the view we see in the browser.
    ---- app.css // for css
    ---- app.test.js // for testing
    ---- index.css //applies style to the body tag
    ---- logo.svg //
    ---- serviceWorker.js

    ### when we run the command "npm start" , index.html file is served in the browser. 
    ### index.html contains the root DOM node. 
    ### next control enters index.js , React DOM renders the app component onto the DOM element specified(root DOM Node)
    ### the app component contains the HTML which is ultimately displayed in the browser.

    ## Components
 


    











