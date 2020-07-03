# Todo-Dapp-Besu

This repo contains a simple Todo dapp that runs on besu using truffle

To run the Todo on besu
1. Clone the repo
2. ```cd Todo-Dapp-Besu```
3. Install dependencies 
   ```npm install```
4. Run the besu dev network 
   ```npm run besu```
5. Compile the contract
   ```truffle compile```
6. Deploy the contract to besu dev network
   ```truffle migrate --network=besu --reset
7. To run the client application
   ```cd client && npm install```
   ```npm run start```
