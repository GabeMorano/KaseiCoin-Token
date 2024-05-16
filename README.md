# KaseiCoin Crowdsale

This project implements a token and a crowdsale contract for the KaseiCoin (KSC) cryptocurrency. The project is built using Solidity and utilizes OpenZeppelin libraries.

## Project Structure

- `KaseiCoin.sol`: Defines the KaseiCoin ERC-20 token.
- `KaseiCoinCrowdsale.sol`: Defines the crowdsale contract for KaseiCoin and the deployer contract.

## Steps to Deploy

### 1. Compile the Contracts

1. Open Remix IDE.
2. Load `KaseiCoin.sol` and `KaseiCoinCrowdsale.sol` into Remix.
3. Compile both contracts using the Solidity compiler version `0.5.5`.

### 2. Deploy the Contracts

1. Open Ganache and start a new workspace.
2. Connect MetaMask to the Ganache network.
3. In Remix, ensure the environment is set to "Injected Web3".
4. Deploy the `KaseiCoinCrowdsaleDeployer` contract with the following parameters:
   - `name`: `"KaseiCoin"`
   - `symbol`: `"KSC"`
   - `wallet`: Your MetaMask account address.

### 3. Interact with the Contracts

1. After deployment, note the `kasei_token_address` and `kasei_crowdsale_address` from the deployed contract.
2. Send Ether to the `KaseiCoinCrowdsale` contract address to participate in the crowdsale and mint new tokens.

## Evaluation Evidence

### Successful Compilations

![KaseiCoin](https://github.com/GabeMorano/KaseiCoin-Token/assets/160795583/6c9d04f3-1c87-4722-bbe3-04ac4d83a863)

![KaseiCoinCrowdsale](https://github.com/GabeMorano/KaseiCoin-Token/assets/160795583/fcaf3040-07bb-4e28-b561-5eb305f6bb8c)

### Deployment

![KaseiCoin_deployed](https://github.com/GabeMorano/KaseiCoin-Token/assets/160795583/40cda5ea-96af-4710-ba20-400b9f381f40)

![Crowdsale_Deployed](https://github.com/GabeMorano/KaseiCoin-Token/assets/160795583/a7ef633c-2ee5-4dc4-9be2-e70bfa75f2fa)

