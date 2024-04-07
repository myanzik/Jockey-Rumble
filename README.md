<h1 align="center">Chaninlink Jockey</h1>
An awesome Horse Race betting game running on Blockchain and powered by Chainlink VRF!<br><br>

* Chaninlink Jockey game built with chainlink vrf and solidity.
* Chaninlink Jockey interacts with Rinkeby Network with help of metamask.

# Basic Workflow
![diagram](https://github.com/Sagar133/RPG-Solidity-Game/blob/elio-blockchain/blockchain/src/assets/diagram.jpg)

# Demo Video
https://www.loom.com/share/5ff6b6af3ec243ef9d9331c0551b2263?sid=ece3b4d8-eb07-4315-8ef9-656f250c5ddf

<!-- GETTING STARTED -->
## Getting Started

Instructions on setting up your project locally.
To get a local copy up and running follow these simple example steps.

### Prerequisites

Make sure you have an Ethereum Wallet provider and NPM/Yarn package managers set up along with NodeJS. NPM can be installed with:
* npm
  ```sh
  npm install npm@latest -g
  ```

### Installation

Following are the instructions for running the web application locally.

1. Get a free API Key at [https://infura.io/](https://infura.io/) , and Etherscan
2. Clone the repo
   ```sh
   git clone https://github.com/myanzik/Jockey-Rumble
   ```
   First navigate to `Jockey-Rumble`
3. First navigate to `Jockey-Rumble` and Install NPM packages
   ```sh
   npm install
   yarn
   ```
4. Enter your API in `.env` inside 
Jockey-Rumble/ folder

   ```JS
   ETHERSCAN_API_KEY="Your ETHERSCAN API KEY"
   RPC_URL="https://polygon-mumbai.infura.io/v3/{YOUR RINKEBY API KEY}"
   MNEMONIC="Seed phrase of your metamask wallet"
   SKIP_PREFLIGHT_CHECK=true
   PRIVATE_KEY="Enter exported private key of your ethereum wallet metamask"
   ```
   
   NOTE: **NEVER SHARE YOUR API KEYS AND PRIVATE KEYS**
   
 5. Build the web application locally:
  ```sh
   npm run dev
   OR
   yarn dev
   ```  

Following are the instructions for running the game locally:
1. First navigate to `Jockey-Rumble/` folder and Install NPM packages
  ```sh
   npm start
   OR
   yarn start
   ```  

<!-- CONTRIBUTING -->
## Contributing

Contributions are what make the open source blockchain community such an amazing place to be learn, inspire, and create. Any contributions you make are **greatly appreciated**.

1. Fork the Project
2. Create your Feature Branch (`git checkout -b feature/AmazingFeature`)
3. Commit your Changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the Branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request
