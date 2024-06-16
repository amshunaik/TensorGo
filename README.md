## Instructions :
1. Download the file in your desktop
2. Install npm modules and node.js in vs code
3. Write command "npm install npm --global" in vs code terminal
4. For Google OAuth access :
   -  log in Google cloud application
   -  Go to API and services page
   -  Click Google Auth and start a new project and create new project
   -  From there you will get the Clied Id and Client key.
   -  Go to credential and click the project which you are using and add the Authorized redirect URIs and Authorized JavaScript origins 
   -  Insert the URI "http://localhost:3000/" , "http://localhost:3000" and "http://localhost:3000/oauth-authorized/google" in Authorized redirect URIs
   -  Insert "http://localhost:3000" in Authorized JavaScript origins.
   -  Save the changes you made.
   -  Go to OAuth Consent Screen and start the production.
   
5. In this repository 2 main file are App.js and node1.js ( App.js in aim folder , node1.js in aim/src/store folder)
6. Open 2 terminal side by side.
7. In the left terminal write following command :
   
     - cd aim
     - npm start

9. In the right terminal write following command :

     - cd aim/src/store
     - nodemon node1.js

10. Then the application will open up and then login into the application and use it. 
