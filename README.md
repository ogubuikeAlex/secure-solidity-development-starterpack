
# Solidity Development Starter File

This is a starter template to get started on writing **SECURITY-CONCIOUS** smart contracts.

I became tired of always setting up projects from scratch and so I created this starter file to speed up my development process.

## Tech Stack

- **Hardhat**
- **EtherJS**
- **Slither**
- **Ethereum security Toolbox by Trail Of Bits**
- **Openzeppelin Contracts**
- **Chainlink Contracts**
- **@nomicfoundation/hardhat-toolbox**
- **@nomiclabs/hardhat-etherscan**
- **hardhat-contract-sizer**
- **hardhat-gas-reporter**
- **prettier-plugin-solidity**

## Related

Here are some related topics

[How To Install Slither](https://medium.com/@ogubuikealex/how-to-install-slither-for-smart-contract-security-testing-cbf058c18e10)

## How To Use

- Install via the command line

```bash
  npm i secure-smartcontract-template
```
or via package.json

```json
 "secure-smartcontract-template": "1.x.x"
```
or fork and clone the project

```bash
  git clone https://github.com/YOUR-USERNAME/secure-solidity-development-starterpack.git
```
- Install dependencies

```bash
  npm install
```

- Run Test
```bash
  npx hardhat test
```
- To run slither on your smart contracts
```bash
  slither .
```
- To run ethereum-toolbox on your smart contracts
Please Note that you should have `docker` set up first before you can run the command below

```bash
  npm run toolbox
```
