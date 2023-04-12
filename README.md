# Stargate Bridger for multiaccounts 

## Script to bridge on Stargate.finance

### You can bridge ETH between arbitrum to optimism, and USDC between polygon and fantom 

Script will loop through wallet and transfer ETH or USDC from the network with from the bigger balance, wait for   
 minutes and loop once again
---
## Before start ##


1. Install python 3.10+
2. Clone repository
3. Install required packages
```commandline
    pip install -r requirements.txt
```
4. Fund your wallets with ETH on arbitrum or optimism if you want to bridget ETH 
### OR
4. Fund your wallets with USDC on fantom or polygon and a bit of matic/fantom for commission if you want to bridge USDC.
5. Create a keys.txt file with private keys following the example of keys.example.txt
---
## Usage ##

For using ETH bridge:

  ```
  python use_eth_bridge.py
  ```


For using USDC bridge:

  ```
  python use_usdc_bridge.py
  ```
