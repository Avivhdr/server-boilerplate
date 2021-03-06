## Setup

The Express application requires a `.env` file.  In the root of the project, create a `.env` file and put the following into it:

```
NODE_ENV=development
DB_STRING=<your db string>
PRIVATE_KEY=<private key>
```

You will also need to start the Mongo DB database using the `mongod` process.  I run this process persistently in the background, but you could also just type `mongod` in your terminal (assuming you have Mongo DB installed).


```

## Quickstart

To start the app, you will need to run both an Express server, and then visit `http://localhost:4200` in the browser.

```
# Start the Express server (http://localhost:3000)
node app.js

```