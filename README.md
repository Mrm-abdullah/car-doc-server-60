 -----------------
 setup server site
 -----------------

1. goto >>>> https://expressjs.com/en/starter/installing.html

2. create index.js and type
const express = require('express')
const app = express()
const cors = require('cors')
require('dotenv').config()
const port = process.env.PORT || 5000;

// middleware
app.use(cors())
app.use(express.json());

3. package.json
"scripts": {
    "start": "node index.js",
  },

4. goto >>>> https://www.npmjs.com/package/cors
5. goto >>>> https://cloud.mongodb.com/v2/6623bee6440aa14866eca3c7#/clusters/connect?clusterId=Cluster0
6. goto >>>> https://www.npmjs.com/package/dotenv
7. goto >>>> https://www.mongodb.com/docs/drivers/node/current/usage-examples/find
8. goto >>>> 
9. goto >>>> 

 -----------------
 Page folder file setup
 -----------------





