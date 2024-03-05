# Decentralized Voting Application

This is a demo application to implement voting in solidity smart contract using ReactJS. 


##Discription
This program is a contract written in Solidity, a programming language used for developing smart contracts on the Ethereum blockchain. The contract has a multiple function that returns the string different different outputs. This program serves as a highly secure platform for voting .introduction to Solidity programming, and can be used as a stepping stone for more complex projects in the future.

## Installation

After you cloned the repository, you want to install the packages using

```shell
npm install
```

You first need to compile the contract and upload it to the blockchain network. Run the following commands to compile and upload the contract.

```shell
npx hardhat compile
npx hardhat run --network volta scripts/deploy.js
```

Once the contract is uploaded to the blockchain, copy the contract address and copy it in the .env file. You can also use another blockchain by writing the blockchain's endpoint in hardhat-config.

Once you have pasted your private key and contract address in the .env file, simply run command

```shell
npm start
```
## Authors

Metacrafter Student Vishal Saini 



## License

This project is licensed under the MIT License - see the LICENSE.md file for details
