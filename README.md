## deVote - blockchain based voting system for pull requests

deVote is a browser extension for decentralised voting of pull requests in GitHub repositories. For the decentralisation of the voting mechanism, smart contracts are used, which run on the Ethereum blockchain or an Ethereum testnet. This project was developed as part of the university course *"Kryptographie und Systemsicherheit"* at the [University of Flensburg](https://hs-flensburg.de/).

## Architecture

## Deployment

## Documentation

#### Browser extension

#### Smart contract

As described in the chapter *Architecture*, there are two different types smart contracts that deVote uses. There is one parent contract (manager contract) and several child contracts (poll contracts). The manager contract must be created manually once and the poll contracts are published by deVote. The process of publishing the manager contract and the necessary configuration for the poll contracts are explained below.

## Credits and Lecture

In addition to [@sebastiangajek](https://github.com/sebastiangajek) help and support, the following resources helped us a lot to realise this project.

* [POA - Part 1 - Develop and deploy a smart contract](https://kauri.io/#article/549b50d2318741dbba209110bb9e350e)
* [Using Web3.js to Deploy Smart Contracts on Moonbeam](https://docs.moonbeam.network/getting-started/local-node/web3-js/web3-contract/)
