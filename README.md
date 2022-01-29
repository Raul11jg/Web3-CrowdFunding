# CryptoCrowdFunding

_A CrowdFunding web using Blockchain - Ethereum
React and Next.js as frontend_

## 

A complete app using React for Frontend and solidity to interact with the Ethereum blockchain. In this case i use Goerli as the testNet.
Ganache is used to test the code.

There is an instance of a contract that can create other contracts.
Users can create a new campaign (deploy a new contract).
You can see all the campaigns ongoing and the manager (who created the campaign) can ask for requests for the project.
He will be able to submit a request to reach a certain amount of money (ethers) and only the users that contributed in this project can vote in order to accept or denied the request. With the majority of votes possitive the smartcontract will execute the transaction and ethers will be sent.
All this flow is using web3 (Metamask as extension).


Screenshot web app:
![Screenshot_CrowdCoin](https://user-images.githubusercontent.com/46672868/151239099-6f4206ad-3e73-4bac-b709-16081b37a0bd.png)
