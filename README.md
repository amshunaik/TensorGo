## Instructions :
1. Download the file in your desktop
2. Install npm modules and node.js in vs code
3. Write command "npm install npm --global" in vs code terminal
4. In this repository 2 main file are App.js and node1.js ( App.js in aim folder , node1.js in aim/src/store folder)
5. In this repository 2 main file are App.js and node1.js ( App.js in aim folder , node1.js in aim/src/store folder)  
6. For Google OAuth access :
   -  log in Google cloud application
   -  Go to API and services page
   -  Click Google Auth and start a new project and create new project
   -  From there you will get the Clied Id and Client key.
   -  Go to credential and click the project which you are using and add the Authorized redirect URIs and Authorized JavaScript origins 
   -  Insert the URI "http://localhost:3000/" , "http://localhost:3000" and "http://localhost:3000/oauth-authorized/google" in Authorized redirect URIs
   -  Insert "http://localhost:3000" in Authorized JavaScript origins.
   -  Save the changes you made.
   -  Go to OAuth Consent Screen and start the production.

7.  Airtable Authentication 
   -  Login to Airtable application
   -  Create a new Base
   -  In it create a table named "Table 2"
   -  Add the attributes which will be stored and set their datatype and value type.
   -  Then click on Help buttion on the top right side ( ?Help) and click on add extension and get the Base ID.
   -  Then Click on your name Icon and go to Developer hub
   -  Click Personal access token and create new token button and get the Token ID and store it as API key and make changes in the node1.js file where we are accessing Airtable
     
8. Automation and integration using Zapier
   - Signup and Login into Zapier
   - on the left side, click on Zaps and create button.
   - In Zapier you can integration as many available applications and apps with zapier and set up the Trigger and Action
   - The first Zap I created is used Webhooks in zapier as trigger and Airtable create event as  action and stored the post request content recieved from the user into Airtable.
   - In the Second Zap I used 3 applications one is Webhooks in Zapier , a number formatter to send the payment user need to do and a Gmail to recieve Invoice/ recieve a mail of successfull payment .
   - Publish both these Zap and open vs code in your PC.
     
9. Open 2 terminal side by side.
10. In the left terminal write following command :
   
     - cd aim
     - npm start

11. In the right terminal write following command :

     - cd aim/src/store
     - nodemon node1.js

12. Then the application will open up and then login into the application and use it. 
