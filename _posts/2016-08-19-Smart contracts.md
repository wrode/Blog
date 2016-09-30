---
layout: post
title: Smart contracts
draft: true
---

Smart contracts are an important part of the enthusiasm surrounding blockchain technology. In this post, I try to explain exactly what a smart contract is.
<!--more-->

First, let's quickly do a recap of the magic analogy in the previous post to explain a blockchain (the original blog post can be found [here](http://allisabstract.com/2016/08/06/Blockchain.html)). For those of you who have not read the previous post, I explain what a blockchain is without using IT jargon by pretending it's based on magic and not technology. <!-- which is of course a complete and utter lie, magic does not exist, and neither does your god.--> A public blockchain can be imagined in the following way:

- An identical agreement is written on a set of enchanted documents.
- Anyone can take part in maintaining this agreement by owning one of these documents.
- Magic rules describe the changes you are allowed to make to a document.<!--the agreement-->
- Any valid change to one document is automatically made to all the other documents.<!--agreement on one document-->

These properties result in each participant owning an identical copy of the same agreement, even though the agreement undergoes continuous change. The illustration below shows how a change to one document is subsequently updated in the other documents:

![Enchanted documents]({{ site.url }}/assets/images/EnchantedDocuments.gif){:style="width:80%; margin: 0 5%"}
The magic analogy above describes **one** set of enchanted documents (blockchain) that follow **one** set of magic rules. Different sets of enchanted documents have different magic rules that control the changes that are allowed to be made to them. The original set of enchanted documents is called Bitcoin, the magic rules for this set of documents are: <!--(super oversimplified, please do not kill me Bitcoiners)-->

1. Each enchanted document contains a list of all accounts and balances.
2. People own accounts, and can send their own bitcoins to other accounts.

In essence, these rules create a digital cash<!--should i write more here, if yes, I should write about Bitcoin being the currency - and all it really is is just a number next to your account on the global digital ledger-->. Below is an illustration of one of these enchanted documents. The number next to each account denotes the amount of bitcoins in that account.
![bitcoin]({{ site.url }}/assets/images/bitcoin.png)
<!--Remove the bitcoin logo from the bottom of the illustration -->
<!--Need to explain that the bitcoins are just the balances on the enchanted documents -->

Another set of documents is called Ethereum. The enchanted documents that make up Ethereum follow very similar rules to Bitcoin:

1. Each enchanted document contains a list of all accounts and balances.
2. Owners of accounts can send transactions to other accounts.

Those of you with an eye for details might have noticed slight differences in wording between the second rule of Ethereum and the second rule of Bitcoin. This difference in wording incorporates how the two sets of documents work differently. 

One of these differences is the fact that not all accounts on the Ethereum enchanted document is owned by people. Instead, the actions of these accounts are controlled by a set of instructions residing on the account.<!--The second difference is that in addition to sending the local currency between accounts, it is also possible to send information.## --> Below is an illustration of one of the enchanted documents on the Ethereum blockchain with some of the accounts controlled by instructions and not people:

![ethereum]({{ site.url }}/assets/images/ethereum.png)

When a set of instructions reside on one of these accounts it is called a **smart contract**. The set of instructions is just computer code, essentially - just logic. If "poked" by a transaction from another account, the smart contract can:

- Compute
- Store information
- Send transactions to other accounts

As mentioned, the account with the code is not controlled by anyone. It is completely autonomous. The original code is written by a person, but once the smart contract code has been uploaded on the blockchain, only the logic in the account dictates the actions of the account.

<!-- Write about smart contracts are a combination of the actual smart contract code and the blockchain--> 

---
A small digression: From the cradle of civilization when money was first invented, people have been able to own money. Eventually, organized groups of people made up legal fictions, which were soon able to own money. Now, for the first time in history, a machine can own it's own money (through smart contracts). The consequences of this is hard to know, but we have interesting times ahead.
<!-- Kneeel for your robot overlords picture.-->

---

### The law of smart contracts

Many people are critical of the name "smart contract", as it is not a real contract - it is not something that needs to be complied with or upheld. Instead, it is a contract in the sense that it executes a set of conditions. If we compare the smart contract with a normal contract, some obvious differences are apparent:

![NormalvsSmart]({{ site.url }}/assets/images/NormalvsSmart.png)

#### Legally binding

First of all, a normal contract has legal consequences in the 'real world'. If the counterparty of a contract does not uphold their part of the agreement, the legal system can be used to hold them accountable. 

On the contrary, a smart contract itself does not have to be upheld by anyone external - it's a set of instructions that self-executes. It's important to note however, that smart contracts only have the ability to change the state of the blockchain. A smart contract itself does not have any precedence in the 'real world' other than being able to transfer the ownership of the  cryptocurrency, which has real world value// other than being able to send the balance of its own account to other accounts//. Any other precedence must be aquired by creating a "legal wrapper" around the state of the blockchain.

#### Trust and predictability

When entering into a normal contract, different elements of understanding/trust play an important role:

The most obvious of these is an understanding of the actual contract, the fine print. The contract lays out the terms and conditions of an agreement in laywer language - which is what you are commiting to. This is why you always carefully read the terms and conditions of your itunes agreement. *You* would never sign an agreement that commits you to providing your firstborn as payment for using their service, [as 98% of people would](http://papers.ssrn.com/sol3/papers.cfm?abstract_id=2757465).

Secondly, the terms and conditions that are layd out in a contract is constrained by a large body of existing law. Which means that you can't be sure how the contract will play out by just looking at the writing in the agreement, the legal context of the contract also plays an important role.

This is usually a safeguard, that makes sure contracts work more as intended, instead of working by just following the specific terms and conditions functions described in the contract.

---

Matt Levine presents how this works in a great [article](http://dealbreaker.com/2013/07/electricity-market-rules-were-not-a-worthy-opponent-for-jpmorgans-brainpower/).

[smart contracts were dumb article](https://www.bloomberg.com/view/articles/2016-06-17/blockchain-company-s-smart-contracts-were-dumb).

Even though JP morgan learned how they could game a contract by following the rules, they were caught in the net of a law against market manipulation (matt Levine has a great article about this)

- e.g. the jpmorgan case. Folow the rules of the agreement, but got caught in another regulation
- Legal framework of the contracts context. (does the case of jp morgan fall within this).
- Trust in the rule of law. (judge not being bribed for example)


Last of all, if you understand the writing in the contract and the actual 
One of the weaknesses here is that a lot of history within law has created regulation to handle problems, even though the conditions are clearly specified - it may also. When the state of California create a set of rules about the California electricity market which jp morgan gamed. JP morgan still had to bear a hefty fine.

<!-- visual explanaition of the elements involved in trusting a normal contract-->

That's why you might be hesitant to go into an agreement with the son of the president in Corruptland, regarding some real estate in Corruptland - the rule of law is broken there. // That's also why investors do not want to invest in Corruptland. Rule of law ensures that the investors are treated fairly. if you invest and get screwed over by the son of the president. (give a example from a corrupt country here)

This is not only the case for Corruptland, when a contract specifies terms of condition which are executed they are not always valid even though the contract exactly as intended. When stupid rules which rational self-interested bankers exploit there is not certainty that you can trust the context of the contract.


For smart contracts, you have 
- The smart contract code (and how this is interpreted by the EVM)
- the Blockchain network as a whole

No regulation wrapper to make things work more as intended.

If there is breach of contract or disagreement, contract law will handle it. 
The smart contract is the law – you need to trust:
- Smart contract code 
- Blockchain

No breach of agreement can exist. A smart contract will act exactly as programmed (note that this might be different from intended).

### Examples of smart contracts

- Give examples of what a smart contract can look like.
- Need to talk about the fact that one smart contract can represent one application - therefore, you do not need a whole new blockcahin for every new idea. Many blockchains are sets of rules that define one specific application. 
- Talk about the fact that even though no person owns it, since it is defined by code it is possible to specify that one account has certain privileges that no one else has, thus rendering it in control by someone else.
- Include the diagram of the abstraction layers of different blockchains. Synereo, etc..



- Compliment smart contract
- TOKENS to represent anything
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

### How to think about smart contracts and blockchains

- The ethereum blockchain is in one sense an abstraction layer below other blockchains (which is why it is ofter refered to as blockchain technology 2.0) such as:
    + Bitcoin
    + Steemit (is steemit just a DAO, or can smart contracts also be developed on its platform)
    + Namecoin etc.

Earlier, if you wanted to create a new application, you would need to create a whole new blockchain (with all the infrastructure). Now that is no longer the case.


Ethereum is not the only Blockchain which enables the use of smart contracts, but it is the biggest public blockchain which is built around this concept. Therefore, this blogpost will focus on the Ethereum blockchain.