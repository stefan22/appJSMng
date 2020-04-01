#  appDevJSMngDB


[meteor](meteor.com)



##  Meteor API Docs

- fullstack JS platform for developing in all devices, all environments:
  app-server, web-browser and mobile applications.
- No devops. Meteor makes shipping JS apps simple, efficient and scalable with Galaxy.



##	Meteor commands

- meteor create [create an app]   
- meteor npm install [install dependencies]   
- meteor [to run in http://localhost:3000]           



<br/>


##	Meteor app



| file                  | desc                                          |
| :-------------------- | :-------------------------------------------- |
| **client/main.js**    | an HTML file that defines view templates      |
| **client/main.css**   | a CSS file to define your app's styles        |
| **server/main.js**    | a JavaScript entry point loaded on the server |
| **test/main.js**      | a JavaScript entry point when running tests   |
| **package.json**      | a control file for installing npm packages    |
| **package-lock.json** | describes the npm dependency tree             |
| **node_modules/**     | packages installed by npm                     |
| **.meteor/**          | internal Meteor files                         |
| **.gitignore**        | a control file for git                        |







<br /><br />

###  error fixed: node-gyp rebuild | installing bcrypt with npm
---------------
 switch from bcrypt to bcrypt-node.js. Same API without native add-ons

- npm install --save bcrypt-nodejs && npm uninstall --save bcrypt
  