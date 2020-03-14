Install Node.js
Open Command Prompt and install cordova and ionic
npm install -g cordova
npm install -g ionic
Navigate to a directory using "CD" and create a new proeject
ionic start <projectname> blank --type ionic1   
Here Ionic1 Is angular js Ionic2 is Angular

Configure platforms
ionic cordova platform add ios
ionic cordova platform add android

Run
ionic cordova build ios
ionic cordova emaulate ios

to run on browser 
ionic serve
