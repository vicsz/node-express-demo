### Creating a node project from scratch

$ mkdir myapp
$ cd myapp

Use the npm init command to create a package.json file for your application. For more information on how package.json works, see Specifics of npm’s package.json handling.

$ npm init
This command prompts you for a number of things, such as the name and version of your application. For now, you can simply hit RETURN to accept the defaults for most of them, with the following exception:

entry point: (index.js)
Enter app.js, or whatever you want the name of the main file to be. If you want it to be index.js, hit RETURN to accept the suggested default file name.

Now install Express in the myapp directory and save it in the dependencies list. For example:

$ npm install express --save

.. Create an app.js file

## Starting the App

node app.js

## Creating the Node distributable package 

Create a tar file (won't work in AWS beanstalk)
npm pack

Create a zip of source files only (exlude node_modules)
npm run zip-source

Create a zip of everything (including node_modules)
npm run zip-all