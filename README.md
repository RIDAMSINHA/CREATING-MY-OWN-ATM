# Creating My Own ATM

This project demonstrates the development of a simple ATM (Automated Teller Machine) using React and Ethereum blockchain technology. The project allows users to connect their MetaMask wallets, view their account balance, deposit and withdraw funds, multiply the value by 2, and transfer ownership of the ATM contract.

## Features

- Connect MetaMask wallet to the ATM
- View account balance
- Deposit and withdraw funds
- Multiply the value by 2
- Transfer ownership of the ATM contract

## Prerequisites

- Node.js (v14.0.0 or higher)
- MetaMask wallet extension installed in your browser

## Getting Started

1. Clone the repository:

```bash
git clone <repository-url>
```

2. Install the dependencies ( IF THE DEPENDENCIES DOES NOT INSTALL CORRECTLY THEN USE --force ):

```bash
cd creating-my-own-atm
npm i
```

3. Open two additional terminals in your VS code.
 
4. In the second terminal type: npx hardhat node.
   
5. In the third terminal, type: npx hardhat run --network localhost scripts/deploy.js.
  
6. Back in the first terminal, type npm run dev to launch the front-end.

7. Open the application in your browser, the project will be running on your localhost. Typically at:

```bash
http://localhost:3000
```

8. Connect your MetaMask wallet and interact with the ATM interface.

## Project Structure

- `src/` - Contains the application source code
  - `components/` - Contains reusable React components
  - `artifacts/` - Contains the contract ABI and artifacts
  - `pages/` - Contains the main application pages
  - `App.js` - Main application component
  - `index.js` - Entry point of the application

- `contracts/` - Contains the Solidity smart contract code

## Technologies Used

- React - JavaScript library for building user interfaces
- Ethereum - Blockchain network for decentralized applications
- MetaMask - Wallet and gateway to Ethereum blockchain
- ethers.js - Library for interacting with Ethereum smart contracts

## Contributing

Contributions are welcome! If you find any issues or want to add new features, feel free to submit a pull request.

## License

This project is licensed under the [MIT License](LICENSE).
```
