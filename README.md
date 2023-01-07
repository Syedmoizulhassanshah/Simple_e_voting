# Simple-E-voting-system-Using-Blockchain-Technology-Live-on-Netlify - DAPP



Follow the steps below to download, install, and run this project.

## Dependencies
Install these prerequisites:
- NPM: https://nodejs.org
- Truffle: https://github.com/trufflesuite/truffle
- Ganache: http://truffleframework.com/ganache/
- Metamask: https://metamask.io/


## Step 1. Clone the project
`git clone https://github.com/Syedmoizulhassanshah/Simple-E-voting-system-Using-Blockchain-Technology-Live-on-Netlify.git

## Step 2. Install dependencies
```
$ cd Simple-E-voting-system-Using-Blockchain-Technology-Live-on-Netlify 
$ npm install
```
## Step 3. Start Ganache
Open the Ganache GUI client that you downloaded and installed. This will start your local blockchain instance.


## Step 4. Compile & Deploy Election Smart Contract
`$ truffle migrate --reset`
You must migrate the election smart contract each time your restart ganache.

## Step 5. Configure Metamask
- Unlock Metamask
- Connect metamask to your local Etherum blockchain provided by Ganache.
- Import an account provided by ganache.

## Step 6. Run the Front End Application
`$ npm run dev`
Visit this URL in your browser: http://localhost:3000

## Live Application link (on Netlify)
https://optimistic-mahavira-eacefc.netlify.app

But in order to interact with it you need install all the dependences.
