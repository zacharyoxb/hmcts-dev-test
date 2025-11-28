# hmcts-dev-test
This repo includes the frontend and backend as submodules for seperate commit histories.

Backend needs the following external variables defined for the db to connect:

DB_HOST
DB_PORT
DB_TABLE_NAME
USERNAME
PASSWORD

Then just use gradle to build and execute:
gradle build
gradle run

This was my database schema I used with mysql:



For the frontend just run these 3 commands in order:
yarn install
yarn webpack
yarn start:dev
