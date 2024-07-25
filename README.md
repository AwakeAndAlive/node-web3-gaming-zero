# node-web3-gaming-zero

Basic Multiplayer Node JS and Web3 Browser Full Game Template (Poker)

Prototype Tecnologies: Web3, MongoDB, Express, React, NodeJS.

- Socket.io is used
- Users queue up for automatic Matchmaking

# Server Setup

Install Dependencies:
Install Node.js, npm, and MongoDB.

In /server, create a .env file:
  MONGO_ATLAS_URI=mongodb://localhost:27017/nome_do_banco
  PORT=3000
npm install && pm2 start server.js --name poker-server

#Client Setup

In /server, create a .env file:
Create .env with:
  REACT_APP_ENDPOINT=http://191.252.192.119:3000

Install and Build (if node 20+, use this legacy openssl):
npm install && export NODE_OPTIONS=--openssl-legacy-provider && npm run build

Serve the Build:
Use serve -s build

# Work in Progress Demo

http://vps53990.publiccloud.com.br/

# Authors

Project by https://github.com/AwakeAndAlive

Thanks to Raghunath at github.com/Raghuboi and Severin at github.com/sevdeawesome for the base codes. 
