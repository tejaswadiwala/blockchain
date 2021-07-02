## How to run:

* Clone this repository.
* Navigate to this repository using the terminal.
* Run `npm i` to install all the dependencies.
* Run `npm run dev`. This will start the first node on localhost:3001.
* Run `HTTP_PORT=3002 P2P_PORT=5002 PEERS=ws://localhost:5001 npm run dev`. This will start the second node.
* For interacting with the application, navigate to `blockchain/app/index.js` to checkout all the get and post endpoints.
