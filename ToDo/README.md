# TodoIonic
Typescript
http://www.typescriptlang.org/docs/tutorial.html

SASS

Node

Ionicframework 
https://ionicframework.com

Ionicviewapp

IonicIcons
https://ionicframework.com/docs/ionicons/



Install ionic app

# Install node
$ node -v
v 8.11.1

You need to have ionic version 6 or up for Ionic 3

# Install ionic cli and cordova cli 
$ npm install -g ionic cordova

$ ionic -v
3.20.0

$ cordova -v
8.0.0

Ionic CLI
- create and test apps
- Scaffolding and generating ionic files
- Typescript compiling and transpiling
- Sass preprocessing
- Integration with ionic cloud services
- Create a blank app

$ ionic start todo blank

Run your app
$ ionic serve 

Run on a device or simulator
$ ionic cordova:run ios 

The build folder consists of www and build. Compiled code is presented under build folder.

SASS is compiled to main.css and Typescript + HTML5 code is compiled under main.js under build folder.

To generate service/provider via ionic cli 
$ ionic generate provider <name-of-service>
Once the service is generated, make the necessary changes under app.module.ts 

To create new pages in ionic
$ ionic generate page ArchivedTodos


ionic login
ionic link
ionic link
ionic upload
Goto physical device, open ionic view device, login using account creds, 




