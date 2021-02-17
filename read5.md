## Getting Started With Node.jss on Heroku

The Heroku Command Line Interface(CLI) requires Git

we will use the CLI to manage and scale your applications, provision add-ons, view your application logs, and run your application locally.
we can use the heroku command from the terminal.
Use the 'heroku login' command to log in to the Heroku CLI.
we need Node.js and npm to work with heroku
we can deploy the code by run 'git push heroku master' on terminal
we Use a Procfile, to explicitly declare what command should be executed to start your app. and we can check which file will run using 'heroku ps'
if we run the bash command 'heroku run bash',it will opens up a shell on the dyno.

### Node.js
Node.js is an open source, cross-platform runtime environment, which allows us to build server-side and networking applications. It's written in JavaScript and can be run within the Node.js runtime on any platform.

Heroku makes it easy to deploy and scale Node.js applications. Run any recent version of Node.js. Deploy apps in seconds using dependency caching.