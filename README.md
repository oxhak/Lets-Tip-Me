# Stellite Funding Platform

Funding platform for the Stellite Blockchain.

In the future it can extend to all types of projects and connect to StellitePay.


# How To (Temporary)

1. Install and run MongoDB locally on port 27017 and with MongoDB Shell (mongo) insert an user :

`use stellite-funding-platform`

`db.users.insertOne( { username: "your_username", email: "your@email.com", password: "$2b$10$YFDBYNu0Pp0.yLarktEQhudQXQLfdrkNFmRYHy1wHMn04H4kXo8ja" } );`

Your user password is `test`

2. Clone this repository :
`git clone https://github.com/oxhak/Stellite-Funding-Platform`

3. Run app.js with Node.js : `node app.js`

4. Open your web browser, go to http://127.0.0.1:3000 and try to Login.
