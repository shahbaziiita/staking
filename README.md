# Staking Coin

## Installation

### Setup

- **Node.js**

      sudo curl -o- https://raw.githubusercontent.com/nvm-sh/nvm/v0.37.2/install.sh | bash
      nvm install 12.18.3
      node -v

- **Truffle**

      sudo npm install -g truffle@5.1.39 --unsafe-perm=true

- **Ganache** installation guide can be found in [here](https://www.trufflesuite.com/ganache).

- **MetaMask** installation guide can be found in [here](https://metamask.io/).

### Commands

- Install necessarily Node.js packages

      npm install

- Deploy smart contracts to the Ethereum blockchain

      truffle migrate --reset
      
- Deploy and run the front-end application

      npm start run

- Copy the private key of the second account (first account is deploy-er of the DApp, second account is the user of the DApp).

- Import the account on Metamask

- For Staking, Stake coin by clicking on Stake button

- For Unstaking, click on unstake coin
      
- Run the scripts to issue tokens

      truffle exec scripts/issue-tokens.js


