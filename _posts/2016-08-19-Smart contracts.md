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
![bitcoin]({{ site.url }}/assets/images/BitcoinDoc.png)
<!--Need to explain that the bitcoins are just the balances on the enchanted documents -->

Another set of documents is called Ethereum. The enchanted documents that make up Ethereum follow very similar rules to Bitcoin:

1. Each enchanted document contains a list of all accounts and balances.
2. Owners of accounts can send transactions to other accounts.

Those of you with an eye for details might have noticed slight differences in wording between the second rule of Ethereum and the second rule of Bitcoin. This difference in wording incorporates how the two sets of documents work differently. 

One of these differences is the fact that not all accounts on the Ethereum enchanted document is owned by people. Instead, the actions of these accounts are controlled by a set of instructions residing on the account.<!--The second difference is that in addition to sending the local currency between accounts, it is also possible to send information.## --> Below is an illustration of one of the enchanted documents on the Ethereum blockchain with some of the accounts controlled by instructions and not people:

![ethereum]({{ site.url }}/assets/images/EthereumDoc.png)

When a set of instructions reside on one of these accounts it is called a **smart contract**. The set of instructions is just computer code, essentially - just logic. If "poked" by a transaction from another account, the smart contract can:

- Compute
- Store information
- Send stuff to other accounts

As mentioned, the account with the code is not controlled by anyone. It is completely autonomous. The original code is written by a person, but once the smart contract code has been uploaded on the blockchain, only the logic in the account dictates the actions of the account.

<!-- Write about smart contracts are a combination of the actual smart contract code and the blockchain--> 

---
A small digression: From the cradle of civilization when money was first invented, people have been able to own money. Eventually, organized groups of people made up legal fictions, which were soon able to own money. Now, for the first time in history, a machine can own it's own money (through smart contracts). The consequences of this is hard to know, but we have interesting times ahead.

![Robot overlords]({{ site.url }}/assets/images/RobotOverlords.png)

---


### Code is law

Many people are critical of the name "smart contract", as it is not a real contract - it is not something that needs to be complied with or upheld. Instead, it is a contract in the sense that it executes a set of conditions. If we compare the smart contract with a normal contract, some obvious differences are apparent:

![NormalvsSmart]({{ site.url }}/assets/images/NormalvsSmart.png){:style="width:120%; margin: 0 -10%"}

#### Legally binding

First of all, a normal contract has legal consequences in the 'real world'. If the counterparty of a contract does not uphold their part of the agreement, the legal system can be used to hold them accountable.

On the contrary, a smart contract does not have to be upheld by anyone, it's a set of instructions that self-executes. It's important to note however, that the smart contact does not have much precedence in the 'real world'. It is only able to send transactions to other accounts on the blockchain, yet these transactions can be balances with real world value.  Any other precedence must be acquired by creating a "legal wrapper" around the state of the blockchain.

#### Trust

When entering into a normal contract, several factors play an important role. The most obvious part is an understanding of the actual contract. The contract lays out the terms and conditions of an agreement in legalese - which is what you are committing to. Therefore, it is important to understand this legalese and how this is interpreted by the legal system. This is why you always carefully read the terms and conditions of your iTunes agreement. *You* would never sign an agreement that commits you to providing your firstborn as payment for using their service, as 98% of people [would](http://papers.ssrn.com/sol3/papers.cfm?abstract_id=2757465).

![Firstborn]({{ site.url }}/assets/images/Firstborn.png){:style="width:60%; margin: 0 20%"}

Secondly, the terms and conditions that are laid out in a contract are constrained by a large body of existing law. This means that you can't be sure how the contract will play out by just looking at the content of the agreement. There are laws that prohibit you from paying with your firstborn, even if you agree to this by signing a contract. Therefore, it is important to understand how this legal context plays in.

---

These contextual laws often work as a safeguard, at times making contracts work as *intended* instead of as *written*. Journalist Matt Levine has a great [article](http://dealbreaker.com/2013/07/electricity-market-rules-were-not-a-worthy-opponent-for-jpmorgans-brainpower/) about JPMorgan receiving a hefty fine, even after following the conditions set forth in a contract. The contract regulated the electricity market, and JPMorgan found a way to game the contract. JPMorgan did not break the rules set forth in the contract, they followed them carefully, but they did break the intent of the contract and where caught in the net of market manipulation laws.

---

Even if you enslave your firstborn to try and uphold your part of a contract (which was [not unheard of](https://en.wikipedia.org/wiki/Nexum) in the early roman republic), there is still a risk that this is not enough. You could sell all your belongings and sell your family into debt bondage, but it might still not cover your obligations in the agreement. The risk of entering into a contract with someone who is not able to fulfill their part of the agreement is called counterparty risk, and must also be taken into account when entering a contract.

Last of all, even if you understand the contract and the legal context you still need to trust in the rule of law. Sometimes, de jure ≠ de facto. That's why you might be hesitant to go into an agreement with the son of the president in Corruptland. The contract is not worth the paper it's written on.<!--That's also why investors do not want to invest in Corruptland. Rule of law ensures that the investors are treated fairly. if you invest and get screwed over by the son of the president. -->
<!-- visual explanaition of the elements involved in trusting a normal contract-->

A smart contract essentially consists of two elements of trust:

1. The content of the contract, and how this is interpreted.
2. The immutability of the blockchain.

Just like with normal contracts, it´s important to understand the actual content of a smart contract when interacting with it. But unlike a normal contract, which is written in legalese and interpreted by the legal system, the content of the smart contract is written in computer code and interpreted by computers. So what does smart contract code actually look like? Below is an example, the code is an extract of a smart contract:


```javascript
function payOut(address _recipient, uint _amount) returns (bool) {
  if (msg.sender != owner || msg.value > 0 || (payOwnerOnly && _recipient != owner))
      throw;
  if (_recipient.call.value(_amount)()) {
      PayOut(_recipient, _amount);
      return true;
  } else {
    return false;
    }
}
```

The smart contract code is the terms and conditions that you are signing up for when interacting with a smart contract. As long as you trust the blockchain that the smart contract resides on, you know that the code will execute exactly as programmed - so no breach of agreement can exist. It is important to note however, that working as *programmed* does not mean that it will work as *intended* - if there are errors in the code.

The second element of trust was briefly mentioned in the above paragraph, and is trust in the blockchain as a whole. Going back to our analogy, the blockchain consists of enchanted documents that can be owned anyone who wants to participate in maintaining the agreement. The magic rules of the enchanted document defines which changes are allowed and which are not. However, if a group of the participants decide to group together and define new rules, they can create their own offshoot of the original blockchain. The new rules for the new blockchain *can* impact the existing smart contracts, but only on the new offshoot blockchain. Creating the new blockchain does not really affect the old blockchain, unless a large portion of the participants care more about the new blockchain and ditch the old one. Only when that happens - when the new contract's rules mess with your smart contract, and when the new blockchain becomes the *de facto* blockchain of the two - are you at risk of the smart contract not working as programmed.

<!-- The creation of offshot blockchains is not necessarily a bad thing though. Almost all of the hard forks to date are upgrades of the magic rules, making the blockchain perform better - the smart contracts on the blockchain remain untouched. There have been a few forks that have changed the state of the contracts however, but these have been extremely controversial. -->
<!-- Therefore, you can trsut the blockchain. It is mostly the smart contract that you have to understand. -->

### Smart contract applications

As we have already established, smart contracts are essentially just a set of instructions residing on a blockchain, written in computer code. This computer code can be written in an infinite number of ways, just like words specifying the terms and conditions of a normal contract can be written in an infinite number of ways. But like words in a contract, there is an infinite number of ways to arrange the code in a smart contract that does not make sense. That's not interesting and no one cares. What is interesting however, are the ways to arrange the logic which does make sense.

<!--If we want (and dont have anything better to do), we could arrange the logic in a way that creates a smart contract that gives compliments. We might want to make it a little stingy however, and only give compliments to the people that send it money. The more money the contract recieves, the better the compliment it could give.-->

After the original bitcoin paper was published, people started imagining new applications of Blockchains. In the previous blogpost, I presented Namecoin, a blockchain for managing domain names in a decentralized manner. In addition to using blockchains for agreeing about ownership of digital assets such as bitcoin and namecoin, people imagined using it for many other types of agreement too, such as ownership of physical assets and defining governance structures.

The challenge was that each blockchain was being built with one application in mind. Every new application required a whole new blockchain. Creating a new blockchain requires a lot of resources, since a set of participants need to start maintaining a new agreement. Smart contracts changed this. The magic rules that define the functionality of one blockchain can be replicated into smart contracts on an existing smart contract blockchain. This means that instead of building a new blockchain for every type of application, it is possible to add several types of applications to **one** blockchain by using smart contracts. You essentially have many blockchains on the same blockchain, and is why some refer to smart contract blockchains as blockchain 2.0.

![Blockchainception]({{ site.url }}/assets/images/Blockchainception.png)

As an example, the blockchains which specify ownership of different types of assets, the "magic document" is essentially just a list of accounts and what they own. Instead of using a whole blockchain for this application, this information can be included in a smart contract. Like the blockchain, the smart contract would essentially be a list of accounts and their ownership, with rules about which transactions are allowed and which are not.

>Smart contracts have the same applications as blockchains.

As we have already established, smart contracts can be used to document the ownership of assets, not only digital, but also physical such as oil, gold, cars and real estate. But just listing who owns what is just the beginning, additional logic can be included.

![godeeper]({{ site.url }}/assets/images/godeeper.jpg){:style="width:60%; margin: 0 20%"}

A smart contract can specify the ownership in a company, and this ownership can easily be transfered by interacting with the contract. The contract can include instructions about how dividends are paid out through the contract. Any dividends that are paid out are automatically distributed to the owners. In addition, the contract can give the owners voting rights relative to their ownership. Owners would send a transaction with their vote to the smart contract - which would .

What I have described above is essentially just a share of a company, in the form of a smart contract. This is the second application where smart contracts have considerable promise; financial instruments. Securities such as stocks, bonds and derivatives can all be created as smart contracts. In the case of a derivative, the logic would define the terms of the contract - such as payouts based on the future price of oil. The contract would listen to events, and make a payment based on the agreement. If the price of oil goes up 20% then perform a payment to account A, if not, make a payment to account B.
  
<!--- We first present ownership, the second application area relates to adding additional logic to this ownership - thats what financial instruments are. But not only do you have additional logic for handling ownership - you also have other logic you could include. Such as a timer to release money, which might help to save money, or way to distribute money to hundreds of different accounts, or multisignature conditions for moving the money around.-->

#### Dapps

Many of the internet applications that you use today, such as Facebook and Google, communicate with back-end servers to fulfill your needs. The complicated technology is hidden behind the front-end interface, so you will never have to communicate directly with the back-end. This is an abstraction layer, which allows you to perform complicated operations (searching the internet) without needing the competence to know how it is done. Interacting directly with smart contracts is also complicated. The blockchain equivalent  of creating an application that hides this complexity behind a front-end interface is called a *decentralized application*, or *Dapp* for short. 

Dapps might consist of several smart contracts that interact with eachother, all seemlessly hidden behind an interface. One example of a Dapp is a decentralized exchange, where ownership can be exchanged without needing to trust the counterparty or third party (the exchange). Another example is a decentralized prediction (or betting) market which is used to predict and verify the outcome of events.

<!--
- through cryptocurrency can incentivise these new structures to exist. Transistion to dropbox and airbnb for computing power.
-->

---

//Need to finish this section - will write something about the consequences of smart contracts for the average person

The ability to send micro transaction and include financial incentives programmatically allows for other types of application. One example is a decentralized Dropbox, in which users pays people to rent out their extra storage capacity for a small sum. This is essentially AirBnB for hard disk space. Related is renting out unused processing power for a small sum.

Smart contracts and blockchains have a large range of potential applications, but many of these are already solved using centralized solutions today. Time will tell which of the smart contract applications will be better than their centralized alternatives.

--

<!--
The last application area that I will cover in this blogpost is Decentralized Autonomous Organizations.

These are organizations "information from vitaliks blog post."
-->

<!--

- Micropayments. Road tolls. - Market based system...
- generall resource payment system.
- Reputation systems.
- 
(something about not looking into the code is stupid, because it is hard to see
- Unless ofcourse you have a standard contract, which the front-end ensures is correct
- something about communicating directly with smart contracts being complicated

- can decentralized prediction markets be used for military reconossance, or business reconosance? Give the actors incentives to give the correct information about a future outcome?

- Example of how tokens can be used to pay for a schooling system through tokens. 

Many useful things can be solved by smart contracts - but might be better solved in other ways. Some people will argue that solving old problems with existing solutions in new blockchain ways is not useful, others would argue with that.

Challenge for smart contracts:
- What happens after contracts are agreed upon is often unpredictable.
- Parties dont have the time or interest to detail every potential outcome up front.
- parties want a level of flexibility
- Smart contracts are very rigid about the commitments and outcomes

- Talk about the fact that even though no person owns it, since it is defined by code it is possible to specify that one account has certain privileges that no one else has, thus rendering it in control by someone else.

- The ethereum blockchain is in one sense an abstraction layer below other blockchains (which is why it is ofter refered to as blockchain technology 2.0) such as:
    + Steemit (is steemit just a DAO, or can smart contracts also be developed on its platform)
- The state of the blockchain is the "current" information residing on it.


Taking people to court to uphold agreement is a very slow, expensive and inefficient - especially for smaller sums.

Other areas where many actors try to form consensus:
- Science
- The governance structure of the society as a whole

-->


