# @ethereum-artifacts/weth9

## Install
```bash
# In your node project directory
npm i @ethereum-artifacts/weth9
```

## Usage
```javascript
// Import artifacts
const weth9 = require('@ethereum-artifacts/weth9');

// Get ABI for WETH9
console.log(weth9.WETH9.abi);

// Get bytecode for WETH9
console.log(weth9.WETH9.bytecode);

// Create ethers.js contract factory for WETH9
const ethers = require('ethers');
const WETH9 = new ethers.ContractFactory(
  weth9.WETH9.abi,
  weth9.WETH9.bytecode,
);
```