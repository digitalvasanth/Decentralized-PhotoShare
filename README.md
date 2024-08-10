## Decentralised PhotoShare
This project enables decentralized image upload and sharing on the blockchain, utilizing Solidity for smart contracts and React for the front-end interface. It allows users to securely upload images to IPFS (InterPlanetary File System) and share access with specified users through smart contract functionality.




## Technologied Used:-
1. Solidity for smart contract development.
2. IPFS for Decentralised storage protocol.
3. React for the UI Interface.

## How to Use:-
1. Clone my repository :

     ```bash
   git clone https://github.com/digitalvasanth/Decentralized-PhotoShare.git
   ```
2. Install dependencies for the hardhat:

   ```bash
   # Navigate to the root directory
   cd Decentralized-PhotoShare
   # Install hardhat dependencies
   npm install
   ```

3. Compile the smart contract for artifacts:

   ```bash
   # Compile Smart Contract
   npx hardhat compile
   ```

 4. Deploy the Solidity smart contract to an Ethereum testnet or local development environment.
   ```bash
   # Deploy Smart Contract
   npx hardhat run scripts/deploy.js --network <network-name>
```
5. Install dependencies for the React front end:
   ```bash
   # Navigate to the React client directory
   cd client 
   # Install React dependencies
   npm install
   ```
6. Run the react application:
   ```bash
   # Start React Application
   npm start
   ```

# Set up environment variables:
a. Obtain API keys for Pinata to interact with IPFS.
b. Update the React component (FileUpload.js) with your Pinata API keys.

# After accomplishment of setup of variables:- 
1.  Install Metamask.
2.  Update Contract Address : after smart contract deployement , make sure of update of App.js within React file.
3.  Upload image before clicking 'Get data'.
4. Access Other Images by clicking 'Get data'.
