# DigiOffice


### Follow the steps below to download, install, and use this DApp Template for your DApp to get started.

## Dependencies
Install these prerequisites to follow along with the tutorial. See free video tutorial or a full explanation of each prerequisite.

- NPM: https://nodejs.org
- Truffle: https://github.com/trufflesuite/truffle
- Ganache: http://truffleframework.com/ganache/
- Metamask: https://metamask.io/

## STEP 1: Clone the project
  ```
   git clone https://github.com/pikachua7/DigiOffice
  ```
  
## STEP 2: Install dependencies
```
  npm install
```

## Step 3. Start Ganache
  Open the Ganache GUI client that you downloaded and installed. This will start your local blockchain instance. 
  
## Step 4. Compile & Deploy your Smart Contract
  You must migrate the smart contract each time your restart ganache.
  ```
  $    truffle compile
  $    truffle migrate
  ```
  
## Step 5. Configure Metamask
  Unlock Metamask
  Connect metamask to your local Etherum blockchain provided by Ganache.
  Import an account provided by ganache.

## Step 6. Run the Front End Application
  ```
  $ npm run start 
  ```
  Visit this URL in your browser: http://localhost:3000
