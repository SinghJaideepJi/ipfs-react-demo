## IPFS REACT DEMO @GBC

Pre-requisites 

- Install go-ipfs from [this](https://dist.ipfs.io/#go-ipfs) link.
- Follow [this](https://docs.ipfs.io/guides/guides/install/) link to install ipfs command-line tools.


npm install
npm run start
npm run build

ipfs add -r build/
added QmPSzRCyF1h2sDAd4QKxhAvH6MGYVUvbdoYVUzUTfKi1Av build
530.43 KiB / 530.43 KiB

In new terminal run ipfs daemon
Check the port number is 8080

In browser open 
http://localhost:8080/ipfs/QmPSzRCyF1h2sDAd4QKxhAvH6MGYVUvbdoYVUzUTfKi1Av/
https://ipfs.io/ipfs/QmPSzRCyF1h2sDAd4QKxhAvH6MGYVUvbdoYVUzUTfKi1Av

Checkout

http://127.0.0.1:5001/webui


## Install JavaScript ABIs

Create a smart contract and deploy on test network.
https://ropsten.etherscan.io/tx/0xd513619b4bdd36b313f9ac5603e58999edc44f1c388541f91a5a26c6c15ae72e

Copy the abi and create abi.json

npm i ipfs-api --save

npm i web3 --save

