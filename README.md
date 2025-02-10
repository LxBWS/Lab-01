# LxBWS - Lab 01

Support material for the Lisbon Blockchain Winter School (Lab 01).

Slides [here](https://drive.google.com/drive/folders/1fxPBCplE0fZyLSNnAXb6cMsrV8XYCH0I)

## Description

Practice: create a test blockchain using Hardhat

### Dependencies
* Hardhat (v2.22.18)
* Node (v18)


### Let's start

Install the dependencies for this project and run the hardhat test blockchain.

```shell
npm install
npx hardhat node
```

Check the output of the last command. Hardhat automatically creates 20 accounts
ready to use with 10,000 ETH.

Load the private key in a wallet of your choice, connect to the network running
locally (the hardhat network runs by default on http://127.0.0.1:8545).