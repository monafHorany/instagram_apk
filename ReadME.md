# Instagrame Apk Mirror

# **_Installation:_**

- cd server
- npm i --save
- npm start
- Then in browser navigate to http://localhost:5000

To Run React server:

- cd client
- npm i --save --legacy-peer-deps
- npm start

The release and variants are already collected and stored in mongoDB database

To Refetch All releases again you can click on Refetch All Releases

**_Used Technologies:_**

- Node.js v18.14.0
- React: 18.2.0
- mongoDB

==================================================================

- The updatable columns are "release name" column and "#variant available" By double click on the cell (I can make all the columns editable but i enabled editing just for these two columns just for demonstration purposes)
- You can grap the mongoDB connections URI from "https://account.mongodb.com/account/login"
- OR if you have mongoDB installed locally in your machine the connection URI will be "mongodb://127.0.0.1:27017"
- Set it in .env file as "DATABASE_URL"
