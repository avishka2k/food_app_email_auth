# email_auth for production.

## Steps : summary
- Import the repository and mark it private
- Clone it to your local system
- perform ```npm install```
- perform ```npm link```
- create the configurations ```npx email-auth-node --generate```
- create a gmail account and allow less secure apps
- create a account on Heroku
- create an app on heroku and connect it with the github repo you created
- publish the server on heroku
- Add a auth.config.dart file in the flutter project with the data from the config file of the generated config
- Work seamlessly with email_auth with your custom production server
