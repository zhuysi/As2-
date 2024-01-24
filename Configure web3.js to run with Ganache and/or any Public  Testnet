const Web3 = require('web3');

// Connect to the Rinkeby testnet using an Infura URL
const web3 = new Web3('https://mainnet.infura.io/v3/ffee5898c7d64a71bdd2ddf9080c3a58');

// Test the connection
web3.eth.getBlockNumber().then((blockNumber) => {
    console.log('Connected to Rinkeby. Block number:', blockNumber);
}).catch((error) => {
    console.error('Error connecting to Rinkeby:', error);
});
