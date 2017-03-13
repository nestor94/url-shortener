##URL Shortener

###Required Dependencies:

- NodeJS 6.3.1 or greater
- MongoDB 3.0 or greater

###Packages Dependencies
- npm install -g mocha
- npm install -g gulp-cli
- npm install -g karma
- npm install -g nodemon

###Setting Up MongoDB Database

####Get into mongo shell then type:
`$ use urlshortener`

`$ db.counters.insert({_id: 'url_counter', seq: 1})`


###Testing Server

`$ cd api`

`$ npm install`

`$ npm test`

**You should see all test passing if everything is ok**

###Running Server

`$ cd api`

`$ npm start`

###Testing Client

`$ cd client`

`$ npm install`

`$ npm test`

**You should see all test passing if everything is ok**

###Running Client

`$ cd client`

`$ npm start`
