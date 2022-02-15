                                      SECRETS WEBSITE

Check the deployed website in this URL: https://kumarajeeva-secrets-website.herokuapp.com/

DESCRIPTION:
The developed website is a "secrets website" where users can share their secrets anonymously. Users have to register and login to submit and access the secrets. The user profiles and secrets are stored in a MongoDB database. This website is developed using Node.js, Express, EJS and MongoDB.

INSTALLATION AND RUNNING:
1) Clone the github repository and store it in your device.
2) Download the latest versions of Node.js and Hyper command terminal.
3) Download a text editor like Atom or Visual Studio Code.
4) Go to the directory folder in Hyper and install npm package manager.
5) Run the command "npm install".
6) This will install the required packages and dependencies
7) This app requires environmental variable like CLIENT_ID and CLIENT_SECRET to activate OAuth google authentication.
8) Go to "Google developers console" and create a project.
9) Go to OAuth Consent screen and type application name and select required API's such as email,profile,openid,etc.
10) Go to "Create credentials" and create "OAUTH client ID".
11) Mention the origin and redirect URLs and click "Create".
12) Copy the "CLIENT_ID" and "CLIENT_SECRET" into a .env file in the project directory.
13) Now head to Hyper terminal and run "node app.js" command to run the project.

*************************Project done by Kumarajeeva Elavarasan***************************
