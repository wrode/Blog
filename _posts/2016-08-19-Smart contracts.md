---
layout: post
title: Smart contracts
draft: true
---

The thought of smart contracts give a lot of blockchain enthusiasts a warm fuzzy feeling in their otherwise cold and calculating insides. In this post, I try to explain exactly what a smart contract is.
<!--more-->

First, let's quickly do a recapp of our magic analogy to explain a blockchain (the original blog post can be found [here](http://allisabstract.com/2016/08/06/Blockchain.html)). For those of you who have not read the previous post, I basically try to explain what a blockchain is by pretending it's based on magic and not technology: <!-- which is ofcourse a complete and utter lie, magic does not exist, and neither does your god.-->

1. Imagine a set of enchanted documents which are all identical.
2. Anyone who wants can own one of these documents.
3. There are some magic rules about which changes you are allowed to make to the documents.
4. Any valid change to one document is automatically made to all the other documents.

![Enchanted documents]({{ site.url }}/assets/images/EnchantedDocuments.gif)

The magic analogy above beskrives **one** set of enchanted documents that follows one set of rules. But another set of enchanted documents can follow another set of rules.

The original set of enchanted documents is called Bitcoin. The Bitcoin magic rules are as follows: <!--(super oversimplified, please do not kill me Bitcoiners)-->

- Each enchanted document contains a list of all accounts and balances.
- People own accounts, and can send their own bitcoins to other accounts.

Below is an illustration of the bitcoin enchanted documents:
![bitcoin]({{ site.url }}/assets/images/bitcoin.png)

<!--Need to explain that the bitcoins are just the balances on the enchanted documents -->
Another set of documents is called Ethereum. The enchanted documents that make up Ethereum follow very similar rules to Bitcoin's:

- Each enchanted document contains a list of all accounts and balances.
- Owners of accounts can send ether to other accounts.

There is one big difference however. Not all accounts on the ethereum enchanted document is owned by people. Some special accounts have no owners. Instead, the actions of these accounts are controlled by a set of instructions residing on the accounts.

![ethereum]({{ site.url }}/assets/images/ethereum.png)

When a set of instructions reside on one of these accounts it is called a smart contract. The set of instructions is just computer code, essentially - just logic. If "poked" by a transaction from another account, the logic can:

- Compute
- Store information
- Send transactions to other accounts

As mentioned, the account with the code is not controlled by anyone. It is completely automomous. The original code is written by a person, but once the smart contract code has been uploaded on the blockchain, only the logic in the account dictates the accounts actions.

<!-- Write about smart contracts are a combination of the actual smart contract code and the blockchain--> 

---
A small digression: From the craddle of civilization when money was first invented, people have been able to own money. Eventually, organized groups of people made up legal fictions, which were soon able to own money. Now, for the first time in history, a machine can own it's own money (through smart contracts). The consequences of this is hard to know, but we have interesting times ahead.
<!-- Kneeel for your robot overlords picture.-->

---

Many people are critical of the name "smart contract", as it is not a real contract. It's not something that needs to be complied with or upheld. Instead, it is a contract in the sense that it excecutes a set of conditions. If we compare the smart contract with a normal contract, some obvious differences are apparent:

![NormalvsSmart]({{ site.url }}/assets/images/NormalvsSmart.png)

1. Legally binding

 First of all, a normal contract has legal consequences in the 'real world'. If the counterparty of an agreement does not uphold their part of the agreement, the legal system can be used to hold the other party accountable.

Is legally binding.
Not something that needs to be upheld - only settled on the blockchain.

Bound by the blockchain.

Blockchains are intertvined with the 'real world', their cryptocurrencies have real world value. But they still do not have any legal precedence outside the blockchain (yet).

2. Trust

Since a normal contract has legal consequences outside the blockchain, if you trust the contract and the legal system.

For a blockchain

3. Privacy
Come to an agreement,

smart contracts are already public
Contracts can be private
Contract code is published to the blockchain; Contracts are public

No breach of agreement can exist. A smart contract will act exactly as programmed (note that this might be different from intended).
 
If there is breach of contract or disagreement, contract law will handle it. 
The smart contract is the law – you need to trust:
- Smart contract code 
- Blockchain



One of the weaknesses here is that a lot of history within law has created regulation to handle problems, even though the conditions are clearly specifies - it may also. I would highly recommend two articles written byMat Levine on the subject. (bring in Matt Levine).


Example

- Compliment smart contract
- Financial instruments
    + Stocks
    + Bonds
    + Options
- Decentralized applications (Dapps)
    + Decentralized stock exchange
    + Decentralized prediction markets
- MtoM
- DAO’s
- Example of tokens created on the ethereum blockchain

- The ethereum blockchain is in one sense an abstraction layer below other blockchains such as:
    + Bitcoin
    + Steemit
    + Namecoin etc.


Ethereum is not the only Blockchain which enables the use of smart contracts, but it is the biggest public blockchain which is built around this concept. Therefore, this blogpost will focus on the Ethereum blockchain.




<!--
Notes:

- It’s not really a smart contract if we look at the original definition – because it is not really a contract by law.
- 
-->