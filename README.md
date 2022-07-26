# This application uses Solidity, python, and streamlit to create an end-to-end NFT certification app.
### General purpose:
Use web3 technologies to mint an NFT on a streamlit front-end application. The NFT should be linked to an IPFS (interplanetary file system) path, 
and found in the Rinkeby test net (etherium chain).

Photos to come!

## Technologies used:
Solidity
Remix
Ganache
MetaMask
Python
Streamlit
Pandas
Pinata
Web3
Pathlib
Dotenv
Requests

## File Structure:
certificate_abi.json is the ABI that represents the solidty smart contract that was developed, tested, and deployed in Remix's front-end app.
toronto_cert.sol contains the solidity smart contract source code.
a .env file is used to hold all API keys and secret keys
The app.py file is used to house functions and streamlit code. 
If I were to create this again, I'd make a file specfically made for helper functions that would be called in the streamlit code.

## Development Challenges:
I found it conceptually challenging to structure an API push. 
Learning to load the solidity contract into the streamlit app was also challenging but very rewarding when the app pushed minted NFTs to the blockchain.
