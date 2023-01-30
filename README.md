# Solana-Mail App

- This is a simple app that allows you to send and receive encrypted emails using the Solana blockchain.
- The app' backend is built using the [Solana Web3.js](https://solana-labs.github.io/solana-web3.js/) library.
- The app's frontend is built using the [React](https://reactjs.org/) library.
- The app's backend is deployed on [Heroku](https://www.heroku.com/).

## How to run the app

```bash
# clone the repository
git clone https://github.com/mstomar698/Solana-Mail-App.git
# Setup Backend
cd Solana-Mail-App/dapp-backend
cargo test
cargo build
$ cargo build-bpf
$ cargo test-bpf
# backend ruinning at :8899
# _____________________________
# Setup Frontend
cd ../dapp-frontend
yarn install
yarn start
# frontend running at :3000
```

### Make sure yor local machine have following prequisites

>

1. Install Rust <br>
2. Install Solana CLI <br>
3. Yarn <br>

> Leave a ⭐ star if you like the project

#### For Contributing to Backend or Frontend section visit

>

1. [Backend](https://github.com/mstomar698/mail-dApp-backend) <br>
2. [Frontend](https://github.com/mstomar698/mail-dApp-frontend)
