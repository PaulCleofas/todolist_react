Simple Todo List using React

STEP 1: Set directory to react/todo_list

STEP 2:

For linux:
    export NODE_OPTIONS=--openssl-legacy-provider


For windows:
    Replace, the following lines in package.json:

     "start": "export NODE_OPTIONS=--openssl-legacy-provider && react-scripts start",
    "build": "export NODE_OPTIONS=--openssl-legacy-provider && react-scripts build",


    with


    "start": "set NODE_OPTIONS=--openssl-legacy-provider && react-scripts start",
    "build": "set NODE_OPTIONS=--openssl-legacy-provider && react-scripts build",

STEP 3: 

npm install --save -s react react-dom react-scripts web-vitals

STEP 4:

npm start



