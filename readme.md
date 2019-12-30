# Simple Video Chat WebRTC

### By using [simple-peer](https://github.com/feross/simple-peer), this web app connects video chat between two clients.

## How To Use

Install dependencies 
- npm install  
- Start - npm start  

For development run watchify - npm run watch  

Open localhost in two browser tabs.

## Use the deployed version on

https://hash-stream.herokuapp.com/

Allow the app to use your mic and camera. The app can be used for upto two person at a time based on who joins first.


## To deploy on Heroku

Install the Heroku CLI
Download and install the Heroku CLI.

If you haven't already, log in to your Heroku account and follow the prompts to create a new SSH public key.

$ heroku login
Clone the repository
Use Git to clone hash-stream's source code to your local machine.

$ heroku git:clone -a hash-stream
$ cd hash-stream
Deploy your changes
Make some changes to the code you just cloned and deploy them to Heroku using Git.

$ git add .
$ git commit -am "make it better"
$ git push heroku master


### Deploy Existing git repo

- heroku git:remote -a hash-stream

Deploy your changes
Make some changes to the code you just cloned and deploy them to Heroku using Git.

- git add .
- git commit -am "make it better"
- git push heroku master





