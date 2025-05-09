# AO Staking dApp Whitepaper

## Overview

AO Staking is a decentralized Web3 application that allows holders of the $AO token to stake, unstake, and claim rewards directly from their wallets. Built for the Sei Network (EVM-compatible), this platform encourages long-term participation through a fair and transparent reward mechanism.

---

## Key Features

- **Stake/Unstake $AO**: Users can stake or unstake any amount or their full balance.
- **Claim Rewards**: Rewards accumulate over time and can be claimed at any moment.
- **Wallet Integration**: Connects seamlessly with MetaMask.
- **Automatic Chain Switching**: Prompts wallet to switch to Sei V2 chain (Chain ID: 1329).
- **Responsive UI**: Designed for accessibility on both desktop and mobile.
- **Real-time Updates**: Balance, rewards, and staked tokens auto-refresh every 5 seconds.

---

## Technical Architecture

- **Frontend**: HTML, CSS, JavaScript.
- **Smart Contracts**: 
  - `AO Token`: ERC-20 standard.
  - `AO Staking`: Custom staking contract managing balances and rewards.
- **Blockchain**: Sei EVM.
- **Contracts**:
  - Token: `0xDa205256568b0D26Df7dE431E5C800CF8d5E7530`
  - Staking: `0x03AC0F8f35Aeeaa22a4A2b48dc04B66DB58Cf2A0`

---

## Sei Network Configuration

```json
{
  "chainId": 1329,
  "chainName": "Sei V2",
  "nativeCurrency": { "name": "Sei", "symbol": "SEI", "decimals": 18 },
  "rpcUrls": ["https://evm-rpc.sei-apis.com"],
  "blockExplorerUrls": ["https://sei.blockscout.com/"]
}
