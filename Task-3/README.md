# Task 3 Issue A Smart Contract Call To The Deployed Smart Contract

1. ==> The screenshot of the console output
<img src="https://github.com/topma/Nervos-Task/blob/main/Task-3/successfully_issued_a_smart_contract_call.png?sanitize=true&raw=true" />

2. ==> The transaction hash from the contract deployment (in text format)
     ```
     0x8bac2292f3ac753ff89c720c1a71abb0d8821dab0b24c09ad323e370f1be8fd5
     ```
     
3. ==> The deployed contract address from the contract deployment (in text format)
     ```
     0xC54517A3D6Fae39b2B2f5E6911C4d0c62bF22a28
     ```
4. ==> ABI for contract you made a call on (in text format)
    ```
     const CONTRACT_ABI = [ {
      "inputs": [],
      "stateMutability": "payable",
      "type": "constructor"
    },
    {
      "inputs": [
        {
          "internalType": "uint256",
          "name": "x",
          "type": "uint256"
        }
      ],
      "name": "set",
      "outputs": [],
      "stateMutability": "payable",
      "type": "function"
    },
    {
      "inputs": [],
      "name": "get",
      "outputs": [
        {
          "internalType": "uint256",
          "name": "",
          "type": "uint256"
        }
      ],
      "stateMutability": "view",
      "type": "function"
    }]; 
     ```
