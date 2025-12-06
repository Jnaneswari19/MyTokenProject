# MyTokenProject
ERC-20 Token Contract built in Solidity and deployed via Remix IDE. Includes full deployment workflow, token metadata, transfer tests, and event verification.
# MyToken (MTK)
## 🧠 Overview
MyToken is a simple ERC-20 compatible token built on Ethereum using Solidity. It demonstrates core token mechanics including metadata, balance tracking, transfers, approvals, and event logging.

## 🔍 Token Details
- **Name**: MyToken  
- **Symbol**: MTK  
- **Decimals**: 18  
- **Total Supply**: 1,000,000 MTK (scaled to 18 decimals)

## ✅ Features
- ERC-20 standard implementation
- Transfer tokens between accounts
- Approve and delegated transfer (transferFrom)
- Emits `Transfer` and `Approval` events
- Tracks balances and allowances

## 🚀 How to Deploy
1. Open [Remix IDE](https://remix.ethereum.org)
2. Create a new file: `contracts/MyToken.sol`
3. Paste the contract code
4. Compile using Solidity version 0.8.x
5. Deploy with constructor inputs:
   - `_name`: `"MyToken"`
   - `_symbol`: `"MTK"`
   - `_decimals`: `18`
   - `_initialSupply`: `1000000`

📸 Screenshot:  
![Step 1: Remix Setup](screenshots/step1_remix_setup.png)  
![Step 2: Contract Structure](screenshots/step2_contract_structure.png)  
![Step 3: Constructor](screenshots/step3_constructor.png)  
![Step 5: Compile Success](screenshots/step5_compile_success.png)  
![Step 6: Deploy Inputs](screenshots/step6_deploy_inputs.png)

## 🛠 How to Use

### 🔹 Token Info
```solidity
name() → "MyToken"
symbol() → "MTK"
transfer(address _to, uint256 _value)
balanceOf(address) → returns uint256
approve(address _spender, uint256 _value)
transferFrom(address _from, address _to, uint256 _value)

decimals() → 18
totalSupply() → 1000000000000000000000000
