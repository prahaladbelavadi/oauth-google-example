This example demonstrates how to use [Express](http://expressjs.com/) 4.x and
[Passport](http://passportjs.org/) to authenticate users using Google.  Use
this example as a starting point for your own web applications.

## Instructions

To install this example on your computer, clone the repository and install
dependencies.

```bash
$ git clone https://github.com/prahaladbelavadi/oauth-google-example.git
$ cd oauth-google-example
$ npm install
$ npm start
```

The example uses environment variables to configure the consumer key and
consumer secret needed to access Google's API.  Start the server with those
variables set to the appropriate credentials.

Do replace `REPLACE_YOUR_GOOGLE_CLIENT_ID_HERE` with your Google Client Id and `REPLACE_YOUR_GOOGLE_CLIENT_SECRET_HERE` with Google Client Secret in the `.env` file.

Open a web browser and navigate to [http://localhost:3000/](http://localhost:3000/)
to see the example in action.

Disclaimer:
This is a derivative of Jared Hanson's repository on an express example on how to do oauth 2.0 with passport for facebook under Unilicense licence.
All my modifications are released under the same license.
This belongs in the public domain.

Reference: https://github.com/passport/express-4.x-facebook-example