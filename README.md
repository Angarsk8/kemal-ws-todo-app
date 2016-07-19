# Todo Basic App (Crystal - Kemal - WebSockets)

## Requirements
* Crystal 0.18.7

## Installation
Before you can run this program you have to install the packages that it uses. You do that with `$ shards install`.

## Run Project
You can run this program in two ways:

1. Compile/build the project using the command line with `$ crystal build src/notes.cr --release` and run the executable `$ ./notes`.
2. Run the program with `$ crystal src/notes.cr` (no compilation required).

*The second is preferred for development.

Once you have run the program, you can open a browser window at [localthost:3000](http://localhost:3000) and see the actual app. You can open the app in several browser windows and see how they change in real time via websockets.

## Live Demo

You can see and use a live demo of the app here: [kemalwstodo.herokuapp.com](https://kemalwstodo.herokuapp.com).

## Update!
You can see a variant of this application that connects to a Postgres database in this repo [kemal-ws-pg-todo-app](https://github.com/Angarsk8/kemal-ws-pg-todo-app).

*Take in mind that this is just a dummy app written in few hours as a proof of concept.
