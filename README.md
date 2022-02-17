                                      SECRETS WEBSITE

Check the deployed website in this URL: https://kumarajeeva-secrets-website.herokuapp.com/

DESCRIPTION:
The developed website is a "secrets website" where users can share their secrets anonymously. Users have to register and login to submit and access the secrets. The user profiles and secrets are stored in a MongoDB database. This website is developed using Node.js, Express, EJS and MongoDB.

INSTALLATION AND RUNNING:
* Clone the github repository and store it in your device.
* Download the latest versions of Node.js and Hyper command terminal.
* Download a text editor like Atom or Visual Studio Code.
* Go to the directory folder in Hyper and install npm package manager.
* Run the command "npm install".
* This will install the required packages and dependencies
* This app requires environmental variable like CLIENT_ID and CLIENT_SECRET to activate OAuth google authentication.
* Go to "Google developers console" and create a project.
* Go to OAuth Consent screen and type application name and select required API's such as email,profile,openid,etc.
* Go to "Create credentials" and create "OAUTH client ID".
* Mention the origin and redirect URLs and click "Create".
* Copy the "CLIENT_ID" and "CLIENT_SECRET" into a .env file in the project directory.
* Now head to Hyper terminal and run "node app.js" command to run the project.

**Project done by Kumarajeeva Elavarasan**
