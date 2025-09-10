# FraudBlock

![GitHub](https://img.shields.io/github/last-commit/yogeshxd/FraudBlock)

```
NOTE: Devlopement of this project has been stopped because I am working on newer projects so this repository will not be receving any updates.
Last Update: Fixed issues with connecting with metamask.
```

### Blockchain based Fake product identification Solution using QR Codes

## Installation & Demo
[![FraudBlock](https://github.com/yogeshxd/FraudBlock/blob/main/Documents/image.png)](https://youtu.be/F01t48jT5wQ)

## Packages Required:-
- Truffle v5.6.7 (core: 5.6.7)
- Ganache v7.5.0
- Solidity v0.5.16 (solc-js)
- Node v16.20.0
- Web3.js v1.7.4
- npm 7.5.1

## Other Requirements:-
1. Any chromium based browser i.e. Chrome 
2. Metamask browser extension
    
## Setup Process 

1. Clone the project
```
git clone https://github.com/yogeshxd/FraudBlock
```
2. Go to the project folder, open terminal there and run following command to install required node_modules:-
```
npm install
```
3. Compile contract source files. (Compilation and deployment can be done using truffle migrate):-
```
truffle compile
```
4. Open Ganache, (to setup local blockchain)
    - crerate new workspace
    - add truffle-config.js  in truffle project 
    - change port to 7545 in server settings (same as port in truffle-config.js)
5. In chrome, open metamask 
   - add new test network using  
        - NETWORK ID (i.e. 5777 ,from Ganache Server settings) 
        - RPC SERVER (i.e HTTP://127.0.0.1:7545 ,from Ganache Server settings)
        - CHAIN CODE (i.e. 1337)
   - import account using private key of any account from local blockchain available in Ganache.
6. In terminal, run following commands:-
- Run migrations to deploy contracts.
```
truffle migrate
```

- To start a server and it will open a homepage (index.html) file in the default browser.
```
npm run dev 
``` 
7. Login to metamask ,and connect the added account to local blockchain by clicking the 'Connect Wallet' button on the homescreen.
8. Interact with website

### Psst... I have also added all the documents(reports, ppts, base paper etc.) incase anyone of you might wanna use it as your minor/major project.
