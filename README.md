---
description: 'Build on FrogSwap and need help? let us know.'
---

## ✨ Building on FrogSwap and KekChain 🐸

## **FrogSwap Contracts:**

**Frog Token Address**: `0xE8C490ec5957E24E7541Fa0CB9eF2788A33Ce094`

**Router Address**: `0x230400bB1b1455ff0936e4e359Da36CC8E0b2f92`

**Factory Address**: `0xfe0139503a1B97F7f6c2b72f4020df7A6c1EE399`

**wKEK Address**: `0x54Bd9D8d758AC3717B37b7DC726877a23afF1B89`

## How to get your token LOGO on FrogSwap:

### 1. Image for the Token Logo <a id="1-image-for-the-token-logo"></a>

> * **File Extension**: `png` . Uppercase `PNG` is considered invalid
> * **File Name**：`logo.png`
> * **Size**: `256px by 256px`
> * **Background**: Transparent is a must

### 2. Token Information File <a id="2-token-information-file"></a>

> * Fork the repository and add the token information (example below) to mainnet.tokenlist.json
> * Create a folder under assets/{blockchainName}/{tokenAddress}
> * Add the token icon (logo.png) under the folder created in the previous step
> * Add the token information in the mainnet.tokenlist.json file, in the format shown below

The sample below shows what information has to be included on the `mainnet.tokenlist.json` file.  
Please make sure that the details are accurate and follows the formatting.  
The contract address should follow the checksum address format \(see next requirement\).

```
{
      "name": "FrogSwap Token",
      "symbol": "FROG",
      "address": "0xE8C490ec5957E24E7541Fa0CB9eF2788A33Ce094",
      "chainId": 420666,
      "decimals": 18,
      "logoURI": "https://raw.githubusercontent.com/FrogSwap/frogamm-mainnet-tokenlist/main/assets/kekchain/0xE8C490ec5957E24E7541Fa0CB9eF2788A33Ce094/logo.png"
},

```
