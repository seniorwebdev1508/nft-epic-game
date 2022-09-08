# About the project

To initialize a new contract I runed:

`mkdir epic-game`

`cd epic-game`

`npm init -y`

`npm install --save-dev hardhat@2.9.9`

`npx hardhat`

and added a new basic project;

To make a contract deploy on local network I runed:

`npx hardhat run scripts/sample-script.js`

To make the deploy on Goerli, first create a account on Alchemy and create a new project, then fill the project key on .env also fill your wallet private key and after:

`npx hardhat run scripts/deploy.js --network goerli`

Then Fill out in constants.js the contract address.

Ps: The project images was uploaded on pinata that is a ipfs provider.

This project is a web3dev bootcamp
