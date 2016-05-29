---
layout: post
title: What is Bitcoin?
intro: Understanding magic internet money
draft: true
---

## Intro
In 2008, Satoshi Nakamoto published the paper [_Bitcoin: A Peer-to-Peer Electronic Cash System_](https://bitcoin.org/bitcoin.pdf). The paper intoduced a technology which allows for a completely new form of digital money. The technology is completely open source and can be reviewed by anyone.

<!--more-->

Bitcoin is like an internet bank, users have online accounts with balances and can send transactions to each other. In order to understand how Bitcoin works, it may be helpful to first understand how digital money works currently.

### How digital money works
A transaction in a bank works the following way:

+ Bob wants to make a payment to Alice
+ He informs the bank that he wants to perform the transaction.
+ The bank controls a ledger with accounts and balances.
+ The bank ensures that Bob has the required balance to perform the transaction to Alice
+ The bank subtracts the transaction amount from Bob’s account and adds it to Alice's account. 

### How Bitcoin is different
Bitcoin consists of a network on the internet which anyone can participate in.
Every participant on the network maintains their own copy of a ledger with all accounts and their balances.
A Bitcoin transaction works the following way:

+ Bob wants to make a payment to Alice.
+ He creates a transaction specifying Alice's account.
+ He proves ownership of his account by signing1 an outgoing transaction. The transaction is sent a network participant.
+ The participant validates the transaction before sending it to its connected peers.
+ This process is repeated until the transaction has propagated through the network.
+ The distributed ledger is then updated based on the transaction.

<iframe src="http://bl.ocks.org/wrode/raw/8de1cb25066dd70cb468/" width="720" height="200" marginwidth="0" marginheight="0" scrolling="no" frameBorder='0' seamless="seamless"></iframe>

### Bitcoin - the technology

The Bitcoin technology uses advanced cryptography to ensure  that the ledger is secure, and that all transactions are based on signatures which cannot be faked.
The participants that maintain the ledger are rewarded1 with bitcoins as an incentive for their work.

+ This reward is how new bitcoins come into existence.
+ This process is called mining.

The ownership of bitcoins is essentially the Bitcoin network agreeing about the balance in your account

+ This agreement is what creates the scarcity of bitcoin.

The value of bitcoin in other currencies is decided based on what people are willing to pay for them on exchanges.



