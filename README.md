# hackathon backend

## Localhost Deployment

[Install MongoDB](https://docs.mongodb.com/manual/tutorial/install-mongodb-on-ubuntu/)

### Setup Firebase

- [Create a new Firebase Project](https://console.firebase.google.com/u/0/?pli=1)
- [Set up firebase admin](https://firebase.google.com/docs/admin/setup?authuser=0)
  - Save the json file to this repository under the name `service-account.json`

* You'll also need to enable `Email/Password` as a sign-in method under authentication

### Start AI service

Check out the AI repository.

<br>

Finally, Look at the .env.sample for an example config.

<br>

## Actual Deployment

idk

## Generate fake users

node genfake/generator.js
node genfake/stories.js

## Clear DB

node dropall.js

## Test DB

run node tests/testsdb.js to see if db is working properly. if not, make sure the .env is correct.
