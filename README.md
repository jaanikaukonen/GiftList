# Gift List

Week 2 project on Alchemy University Ethereum Developer Bootcamp. Creates a Merkle Tree from the list of names and then verifies if the name is in the list or not. Change the name that is being checked against the merkle tree on the client side index.js name variable.

To get started with the repository, clone it and then run `npm install` in the top-level directory to install the depedencies.

## Client

You can run the client from the top-level directory with `node client/index`. This file is a script which will send an HTTP request to the server.

## Server

You can run the server from the top-level directory with `node server/index`. This file is an express server which will be hosted on port 1225 and respond to the client's request.
