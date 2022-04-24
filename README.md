# Inbox-updated

![INBOX__;)](https://user-images.githubusercontent.com/79961524/162019865-e7fa1d4d-9774-41b8-b981-290f614289ca.png)

In this project web3 javascript library is used along with the solidity language. I have deployed a fairly basic smart contract onto the rinkeby test network. It is deployed at address 0x44DB4F776e837f4C2076710Ff4b00bd5EaDb0839.

I first tested the contract on the ganache local network and wrote tests using the mocha test framework. Then I used truffle's HDWalletProvider as a provider and the Infura API to connect to the rinkeby test network.

NOTE:- To run this application, add a scripts.js file in the INBOX_UPDATED folder and add the following code

```
const seedPhrase = "YOUR 12 WORD SEED PHRASE"
const rinkebyInfuraKey = "YOUR INFURA KEY FOR RINKEBY NETWORK"

exports.seedPhrase = seedPhrase;
exports.rinkebyInfuraKey = rinkebyInfuraKey;
```

This was a project in the Ethereum And Solidity The Complete Developers Guide : Udemy course
