# Module-20-Challenge

[![Screen-Shot-2022-05-22-at-9-44-31-PM.png](https://i.postimg.cc/BQB6PXM2/Screen-Shot-2022-05-22-at-9-44-31-PM.png)](https://postimg.cc/BXtsdQWv)

# Background

In this challenge a fintech startup company has recently hired me. This company is disrupting the finance industry with its own cross-border, Ethereum-compatible blockchain that connects financial institutions. Currently, the team is building smart contracts to automate many of the institutions’ financial processes and features, such as hosting joint savings accounts.

To automate the creation of joint savings accounts, I’ll create a Solidity smart contract that accepts two user addresses. These addresses will be able to control a joint savings account.

My smart contract will use ether management functions to implement a financial institution’s requirements for providing the features of the joint savings account. These features will consist of the ability to deposit and withdraw funds from the account.

---

## Technologies

We'll be using Python and the following libraries to run and read our data. 

* [Solidity](https://docs.soliditylang.org/en/v0.8.14/)  - Solidity is an object-oriented, high-level language for implementing smart contracts. Smart contracts are programs which govern the behaviour of accounts within the Ethereum state. Solidity is a curly-bracket language designed to target the Ethereum Virtual Machine (EVM). It is influenced by C++, Python and JavaScript.

* [Remix IDE](http://remix.ethereum.org/) - allows developing, deploying and administering smart contracts for Ethereum like blockchains. It can also be used as a learning platform.

---
## Installation Guide

In this challenge I used [Remix IDE](http://remix.ethereum.org/) to compile to deploy our contracts.

---
## Usage
* Create additional user input areas in the Streamlit application. 

```java
pragma solidity ^0.5.0;

contract JointSavings {

/*
    Inside the new contract define the following variables:
    - Two variables of type `address payable` named `accountOne` and `accountTwo`

    - A variable of type `address public` named `lastToWithdraw`

    - Two variables of type `uint public` named `lastWithdrawAmount` and `contractBalance`.

*/

    address payable public accountOne;
    address payable public accountTwo;
    address public lastToWithdraw;
    uint public lastWithdrawAmount;
    uint public contractBalance;
}
```
---
## Interacting with deployed Smart Contract 

* Execution of the setAccounts, deposit, lastToWithdraw, and lastWithdraw Amount functions.

[![Screen-Shot-2022-05-22-at-9-39-01-PM.png](https://i.postimg.cc/bwZTwcRc/Screen-Shot-2022-05-22-at-9-39-01-PM.png)](https://postimg.cc/LJMfxW7N)

---

## Contributors

Brought to you by Elgin Braggs Jr.

---
## License

MIT