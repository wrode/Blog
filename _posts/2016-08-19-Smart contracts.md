---
layout: post
title: Smart contracts
draft: true
---

The thought of smart contracts give a lot of blockchain enthusiasts a warm fuzzy feeling in their otherwise cold and calculating insides. In this post, I try to explain exactly what a smart contract is.
<!--more-->

First, let's quickly do a recapp of our magic analogy to explain a blockchain (the original blog post can be found [here](http://allisabstract.com/2016/08/06/Blockchain.html)). For those of you who have not read the previous post, I basically try to explain what a blockchain is by pretending it's based on magic and not technology: <!-- which is in fact a complete and utter lie, magic does not exist, and neither does your god.-->

1. Imagine a set of enchanted documents which are identical.
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

Another set of documents is called Ethereum. The enchanted documents that make up the Ethereum blockchain follow very similar rules to the Bitcoin blockchain:

- Each enchanted document contains a list of all accounts and balances.
- Owners of accounts can send ether to other accounts.

There is one big difference however. Not all accounts on the ethereum enchanted document is owned by people. Some special accounts have no owners. Instead, the actions of these accounts are controlled by a set of instructions residing on the accounts.

![ethereum]({{ site.url }}/assets/images/ethereum.png)

When a set of instructions reside on one of these accounts it is called a smart contract.<!-- Write about smart contracts are a combination of the actual smart contract code and the blockchain--> Ethereum is not the only Blockchain which enables the use of smart contracts, but it is the biggest public blockchain which is built around this concept. Therefore, this blogpost will focus on the Ethereum blockchain.

Its not a contract in sense –> needs to be upheld/complied with
But execute a set of conditions
Essentially, - just logic residing on blockchain account. When an account is “poked” it can:

A smart contract is 
- Compute
- Store information
- Send transactions to other accounts

Code written by person, but once on the blockchain – the person loses control – the code dictates the actions.

---

A small but interesting digression: From the craddle of civilization when money was first invented, people were the only ones to be able to own it. Then, legal fictions were suddenly able to own money. Now, for the first time, a machine can own money. The consequences of this is hard to know.

<!-- Kneeel for your robot overlords picture.-->

---


