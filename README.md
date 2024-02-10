# Smart Contract Management

## Description

This program is a simple project written in Solidity, React/JavaScript.

## Getting Started
After cloning the github repo in gitpod by adding 'gitpod.io/#' at the beggining of repo link, you will want to do the following to get the code running on your computer.

1. Inside the project directory, in the terminal type: npm i
2. Open two additional terminals in your VS code/Gitpod
3. In the second terminal type: npx hardhat node
4. In the third terminal, type: npx hardhat run --network localhost scripts/deploy.js
5. Back in the first terminal, type npm run dev to launch the front-end.

### Setting Metamask Wallet
Then add the new network inside metamask wallet and fill
   1. RPC url from ports-> copy address of port 8545
   2. Chain Id = 31337
   3. Currency Symbol =ETH

Then add your account to metamask wallet by pasting the private key of account #0 from terminal 2 at the import account option.

### Deployment 
After this, the project will be running on your localhost. 
Typically at http://localhost:3000/# Smart-Contract-Management

open project then click on connect Metamask Wallet and than perform transactions.

## Authors

Ramesh 
[@ramesh](https://www.linkedin.com/in/ramesheorann/)


## License

This project is released under the [MIT License](LICENSE).
