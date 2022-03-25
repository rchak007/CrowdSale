![mars](Images/mars.png)



# CrowdSale

KaseiCoin will be a fungible token that’s ERC-20 compliant. This will launch a crowdsale that will allow people convert their money to KaseiCoin.



## Background

After waiting for years and passing several tests, the Martian Aerospace Agency plans to become part of the first human colony on Mars. This project will develop a monetary system for the new Mars colony. This new system will be implemented on blockchain technology and to define a new cryptocurrency named **KaseiCoin**. (Kasei means Mars in Japanese.)



## Smart Contracts

Below are the 2 Solidity contracts created:

[**KaseiCoin.sol**](https://gist.github.com/rchak007/ee86627076c9b495042140f5044d0f5a#file-kaseicoin-sol)

[**KaseiCoinCrowdsale.sol**](https://gist.github.com/rchak007/5992c07657ac6221a3c0443d48f196c5#file-kaseicoincrowdsale-sol)







Created a fungible token that’s ERC-20 compliant. This token will be minted by using a `Crowdsale` contract from the OpenZeppelin Solidity library.

The crowdsale contract will manage the entire crowdsale process. This process will allow users to send ether to the contract and receive KaseiCoin tokens, or **KAI**, in return. The contract will automatically mint the tokens and distribute them to a buyer in one transaction.













