# Smart Contract on Sepolia Testnet

This repository contains the 'Message' smart contract deployed on the Sepolia testnet. This project was created as part of my learning journey to understand how things work in blockchain development.
I've got the Sepolia Ethereum from [Google Cloud's Web3 Faucet](https://cloud.google.com/application/web3/faucet). 

- **Contract Code:** `message.sol`
- [Deployed contract](https://sepolia.etherscan.io/tx/0xd8dc35111baec2857bfe80b9a1acdd5ced3c1a27a25a454d3bf90501db848a04)

## Steps to Run on Remix IDE

1. **Open Remix IDE:**
   - Visit [Remix Ethereum IDE](https://remix.ethereum.org/).

2. **Add the Contract Code:**
   - Copy the Solidity code from this repository and paste it into a new file in Remix with a `.sol` extension.

3. **Set Compiler Version:**
   - In Remix, go to the "Solidity Compiler" tab.
   - Set the compiler version matching the pragma in the contract (e.g., `^0.8.x`).
   - Click "Compile."

4. **Deploy the Contract:**
   - Go to the "Deploy & Run Transactions" tab.
   - Select **Injected Provider - MetaMask** as the environment.
   - Ensure you are connected to the Sepolia testnet in MetaMask.
   - Deploy the contract.

5. **Interact with the Contract:**
   - After deployment, use the Remix interface to interact with your contract.
  
## Notes
- This project is purely for learning purposes to explore how blockchain technology and smart contracts work.



