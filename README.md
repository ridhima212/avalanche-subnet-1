# Avalanche-Subnet-1
- - -
### Steps:

1. Open Remix IDE:
   - Navigate your web browser to Remix IDE.

2. Import Contracts:
   - Copy the contents of `ERC20.sol` and `vault.sol`.
   - Within Remix, create new files named `ERC20.sol` and `vault.sol`.
   - Paste the respective contents into each file.

3. Compile Contracts:
   - Within Remix, access the "Solidity" tab.
   - Choose the appropriate version for the Solidity compiler (e.g., ^0.8.17).
   - Click the "Compile" button to compile the contracts.

4. Deploy Token Contract:
   - Switch to the "Deploy & Run Transactions" tab.
   - Select `ERC20.sol` in the contract dropdown.
   - Click the "Deploy" button to initiate the deployment of the ERC-20 token contract.

5. Copy Token Address:
   - Upon deployment, copy the token contract address from the Remix console.

6. Deploy Vault Contract:
   - Choose `vault.sol` in the contract dropdown.
   - Paste the ERC-20 token contract address into the constructor parameter for Vault.
   - Click the "Deploy" button to deploy the vault contract.

### Interact with Contracts:

Once deployed, interact with the contracts through the provided functions:
- Connect your EVM Subnet to Remix for transaction execution.

## License:

This project is licensed under the MIT License. Refer to the LICENSE file for details.
- - -
