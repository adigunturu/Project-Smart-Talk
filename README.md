## Stack

- Node.js
- Express.js
- Socket.IO
- PeerJs

## How to install locally

Clone this repo
Install PeerJS globally.

    npm i -g peerjs

Now to install all required node modules

    npm i

## Localhost serve

Run Server

    node server

Server Started on Port 3000.

Run PeerJS Server in separate terminal.

    peerjs --port 3001

PeerJS Server Started on Port 3001.

Open browser and goto http://localhost:3000/

## For Heroku

Make a server app on Heroku for the Prototype: project-smart-talk

Make a peerjs app on Heroku for peer connection (multiple users):
https://elements.heroku.com/buttons/peers/peerjs-server - Click the Deploy On heroku Button - Pick a name for the server: smart-talk-peerjs - In the new peer function put this: secure:true,
host: "smart-talk-peerjs.herokuapp.com",
port: 443
