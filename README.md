**ERC20 Token and Vault Contract on Subnet**

### Overview
This project consists of deploying two smart contracts onto a Subnet: an ERC20 token contract and a Vault contract. The ERC20 token contract implements a standard token interface following the ERC20 standard, allowing users to transfer tokens between addresses. The Vault contract provides a secure storage solution for tokens, enabling users to deposit and withdraw tokens with additional security features.

### ERC20 Token Contract
The ERC20 token contract provides the following functionalities:
- Transfer tokens between addresses.
- Approve spending of tokens by another address.
- Check the balance of an address.
- Allowance mechanism for delegated token spending.

### Vault Contract
The Vault contract serves as a secure storage solution for tokens and offers the following features:
- Deposit tokens into the Vault contract.
- Withdraw tokens from the Vault contract.
- Additional security measures to safeguard deposited tokens.

### Deployment onto Subnet
The ERC20 token contract and Vault contract have been deployed onto a Subnet, ensuring decentralized execution and network security. Deploying contracts onto a Subnet offers resilience against centralized failures and enhances the overall reliability of the system.

### Usage
1. **Interacting with ERC20 Token Contract**: Users can transfer tokens between addresses, check balances, and approve spending using the functions provided by the ERC20 token contract.
2. **Utilizing Vault Contract**: Users can deposit tokens into the Vault contract for secure storage and withdraw tokens when needed. The Vault contract ensures the safety of deposited tokens through its security measures.

### Dependencies
- **Subnet**: The smart contracts are deployed onto a Subnet, ensuring decentralized execution and network security.
- **Solidity**: The smart contracts are written in Solidity, a programming language for Ethereum smart contracts.

### License
This project is licensed under the MIT License. See the SPDX-License-Identifier for each contract deployed onto the Subnet.
