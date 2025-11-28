# hmcts-dev-test

## Project Structure

This project uses Git submodules to manage separate repositories - therefore you need to initialise submodules:
```bash
git submodule update --init --recursive
```

## Setup

The db I used was mysql.
Backend needs the following external variables defined for the db to connect:

```bash
DB_HOST=your_db_host
DB_PORT=your_db_port
DB_TABLE_NAME=your_table_name
DB_USERNAME=your_db_username
DB_PASSWORD=your_db_password
```


## Running
Then just use gradle to build and execute from within the backend folder:
```bash
gradle build
gradle run
```

This was my database schema I used with mysql:

<img width="785" height="280" alt="schema" src="https://github.com/user-attachments/assets/2594c1e0-edcf-415b-a590-3efc2ccece0f" />


For the frontend just run these 3 commands in order:
```
yarn install
yarn webpack
yarn start:dev
```
