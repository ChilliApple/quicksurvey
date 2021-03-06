# Project
Quick Survey/Poll between class teacher and students, could be used as a feedback form, the teacher can organize some kind of voting among students, or create a general survey for students.

## Getting Started

A NodeJS app for teacher to create some Poll/Survey among their students, socket.io and Angular JS create a poll with real-time update.

### You need:
```
* NodeJS
* AngularJS 1.0.8 
* Bootstrap 3
* PostgreSQL DB 9.3
* Express
* Socket.io


```

### Installation
``` 
$ git clone https://github.com/ChilliApple/quicksurvey.git
```
```
cd <installation folder>
```
OR 
`$ cd quicksurvey/`

```
npm install
```

Once all the dependencies installed for the project, import schema `postgres_db.sql` and `quickpoll-survey-schema.backup` from `schema/` folder.
You can Edit database connection string from `models/Poll.js`

## To run the app
```
node app
```
Go to browser and run
```
http://localhost:8000
```
## License
This project is licensed under the [MIT License](https://github.com/ChilliApple/quicksurvey/blob/master/LICENSE)
