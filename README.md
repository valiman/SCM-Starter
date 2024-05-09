# Ethereum DApp Starter Kit with Next.js and Hardhat

This starter kit serves as a solid foundation for building decentralized applications (DApps) on Ethereum, utilizing Next.js for the front-end and Hardhat for smart contract development on Ethereum. It includes a simple Solidity contract and a React setup for interfacing with the blockchain through ethers.js.

## Getting Started

Follow these instructions to set up the project locally:

1. **Clone the Repository:**

   ```bash
   git clone https://github.com/your-username/your-repo.git
   ```

2. **Navigate to Project Directory:**

   ```bash
   cd your-repo
   ```

3. **Install Project Dependencies:**

   ```bash
   npm install
   ```

4. **Setup Environment:**

   - Open three separate terminal windows in VS Code for the subsequent steps.

5. **Start a Local Ethereum Node:**

   In the second terminal window, run:

   ```bash
   npx hardhat node
   ```

6. **Deploy the Smart Contracts:**

   In the third terminal window, execute:

   ```bash
   npx hardhat run --network localhost scripts/deploy.js
   ```

7. **Launch the Front-end:**

   In the first terminal window, run:

   ```bash
   npm run dev
   ```

8. **Open in Your Web Browser:**

   Visit [http://localhost:3000/](http://localhost:3000/) to see the application.

## Project Structure

- **`contracts/`**: Contains the Solidity contracts.
- **`artifacts/`**: Stores compiled contracts and their artifacts.
- **`scripts/`**: Includes scripts for deploying the contracts.
- **`frontend/`**: Holds the Next.js and React components for the DApp's interface.
- **`hardhat.config.js`**: The configuration file for Hardhat.
- **`next.config.js`**: The configuration file for Next.js.
- **`package.json`**: Defines the project's dependencies and other metadata.
- **`README.md`**: Provides documentation about the project.

This template is designed to be flexible, allowing for customization and extension as needed to build various Ethereum DApps.

## Additional Setup Details

- Before you begin, ensure that Node.js and npm are installed on your system.
- Install the MetaMask browser extension for wallet interactions within the DApp.
