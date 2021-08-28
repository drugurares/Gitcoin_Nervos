Gitcoin: 11) Use A Tron Wallet To Execute A Smart Contract Call

1. A screenshot of the accounts you created:

![alt text](https://github.com/drugurares/Gitcoin_Nervos/blob/main/task11/1accountCreated.PNG?raw=true)

2. A link to the Layer 1 address you funded: https://explorer.nervos.org/aggron/address/ckt1qyq8derewwh8up0qhg8666uu2rd4dmc2dxrswgdgz9

3. A screenshot of the console output immediately after you have successfully submitted a CKByte deposit to your Tron account on Layer 2:

![alt text](https://github.com/drugurares/Gitcoin_Nervos/blob/main/task11/3TransferToTron.PNG?raw=true)

4. A screenshot of the console output immediately after you have successfully issued a smart contract calls on Layer 2:

![alt text](https://github.com/drugurares/Gitcoin_Nervos/blob/main/task11/4SmartContractCall.PNG?raw=true)

5. The transaction hash of the "Contract call" from the console output (in text format): 0x49cdb00e88d2caa0d4c957119eb642c39a0d61afddc3fd1ed6a44eda4a06860f


6. The contract address that you called (in text format): 0x308AFa2b62e9750876dA65Ef855d1AF6E571a968


7. The ABI for contract you made a call on (in text format): 
[
    {
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
    }
]

8. Your Tron address (in text format): TY9z7scn3qtDVWzd8k9r4Y5iYTXEZoumAH