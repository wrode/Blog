---
layout: "post"
title: "Blockchain"
date: "2017-02-05 11:36"
draft: true
---

<!--more-->
*This post is the second post in a series on blockchain technology, have a look at the introduction post to get an overview of the posts*

In the last post, I wrote about how some types of agreement are fundemental to the functioning of societies. But how does this relate to blockchain technology?

Blockchain technology is essentially just a new way of handling agreements. The big difference between blockchain technology and existing methods, is that a blockchain agreement is not handled centrally by one authority.

In order to illustrate the difference, let us take a closer look at the agreement relating to the ownership of money. We'll pretend that banks maintain the agreement about who owns what using pen and paper. The bank has a document with a list of all the customers, their accounts and their corresponding balances (this is *the agreement*). Every time a customer wants to send some money, they notify the bank, and the bank updates *the agreement* by subtracting some money from one account and adding it to another.

One day, the customers of the bank decide that they do not want the bank to be in charge of maintaining *the agreement* anymore. In fact, they do not want any single authority to maintain it. They decide that anyone can take part in the maintainance of the agreement if they wish. Several people from the crowd accept to take on this role. Let us call the people who participante in maintaining the agreement *peers*. In order to maintain the agreement about who owns what in this new decentralized manner, each peer has their own copy of the paper document with the full agreement, which includes all owners of the currency, their accounts and their corresponding balance. There is no longer one single paper document on which the *true* agreement is written, every peer owns a copy.

![Peers][1]{:.img70}

Any time there is an update to this agreement, all the peers will need to update their agreement - since of course, the agreement should not vary between the peers. In order to ensure that all the peers have the same agreement documented, they would need to meet, agree upon the update, update the agreement, and then sign each others document.

This might be fine if the agreement in question did not change, or if it only changed once every 10 years. The problem arises when you have an agreement which changes often. If all the peers needed to meet, update and sign a new version of the document every time someone makes a bank transaction, this system would be extremely inefficient.

Blockchain to the rescue! Blockchain technology enables peers to efficiently maintain an up-to-date agreement. Once you start asking *how* Blockchain technology does this you start venturing down the rabbit hole and things can get IT jargony very quickly. Fortunately, we can pretend that Blockchains are based on *magic* instead of fancy *technology*.

![You're a wizard][2]{:.img70}

Using the magic analogy, a blockchain can be imagined the following way:
- An identical agreement is written on a set of enchanted documents.
- Anyone can take part in maintaining this agreement by owning one of these documents.
- Rules describe the changes you are allowed to make to a document.
- Any valid change to one document is magically made to all the other documents.

These magic properties ensure that all the peers have an identical and up-to-date copy of the agreement. There is no central authority which owns the definitive agreed upon state, all the peers have their own a copy of this state. This is why Blockchains are referred to as decentralized; there is no central controller of the true agreement.

![Enchanted documents][3]{:.img90}

<!-- Blockchains are of course not based on magic, but on a high conceptual level, this simplification is good enough. Blockchains, like sets of enchanted documents, can follow different rules about how to update the agreed upon state. -->
The rules of the enchanted documents can vary between different sets of documents. In the example at the start of this post, we looked at an agreement about the ownership of money. The magic rules of these documents would be:

1. Each enchanted document contains a list of all accounts and their corresponding balances.
2. People own accounts, and can send the balance in their own account to other accounts.

In essence, these rules create a digital cash.

Do not think of the balance being sent from A to B like physical cash. Instead remember that a transaction in this case is just an update of the agreement. Just like a bank would change the balance of two accounts to create the transaction. The same applies to this blockchain transaction. The illustration below illustrates this difference:

![AtoB][4]{:.img70}

"But wait" you may think. "You are just changing a number next to one account and adding it to another". And it exists only on this distributed agreement. Not a lot of people actually accept that this thing is valuable....

Unlike other money which is legal tender and everyone accepts.

The balance on the agreement is nothing more than a number written next to the account that you own. I can't go to a bank and ask for the.

This balance only has a fiat value because some people are willing to trade some of their own dollars to have a higher balance next to their account on the blockchain.

<!-- WHy does bitcoin have any value? Explain. mIt is important to note that the only reason Bitcoin has any value, is because people believe that bitcoin is valuable, and are willing to exchange bitcoin for dollars or euros-->
---

The most famous example of the currency blockchain above is called bitcoin.

Bitcoin is just one of many blockchains. Why spend so much time explaining the rules for this one. The reason is that all public blockchains need to have its own list of accounts and balances. Therefore, all blockchains have their own currencies.

All public blockchains need this feature. Without a native currency to reward to the participants of the network. There is no incentive for the peers to participate in maintaining the agreement.

After Bitcoin was first published and recieved attention, additional functionality was added to the other blockchains.

One of the first ones were Namecoin...

Storj

Tokens

Go on to talk that it is really about programmable ownership.
->
Many different types of applications
->
Enter Ethereum

Another set of enchanted documents could be defined by rules about how to handle agreements which are written on the enchanted document. The enchantment would ensure that any agreement written on the enchanted document was upheld. Blockchains with these rules also exists, the most famous of which is called Ethereum. Agreements, written as code, can be uploaded to the blockchain.  In a world of magic, these agreements would ensure that the agreement was upheld in the physical world - not only on the enchanted document. In reality, a blockchain does not yet have any legal precedence outside the blockchain - and so an agreement on a blockchain can only be enforced on the blockchain.

Agreements on the blockchain have been named *Smart Contracts* and deserve a blog post of their own.


---


<!-- What to write next?

- Could write about:
  - Talk about blockchain enabling programmable ownership.
  - Comparision of public blockchain, vs permissioned blockchain vs a database as a way to store information
  - Internet analogy (permissionless blockchain, permissionless innovation)
  - Challenges with keeping a distributed agreement
    - Making sure that people are honest...
    - Magic does not exist. The rules are maintained by mathematics (cryptography, and hashing)
    - Securing the agreement (through mining)
      - Peers are rewarded financially
    - Security in terms of key
    - Magic key analogy? If someone takes this they can also pretend that they are you and take your money.
    - Talk about transactions about updates to the agreement.
    - Hacks - example, the exchange -->

<!--
why does it matter...

This also means that there is no central authority who can independently change the rules of the blockchain. The rules are already set in the blockchain, and a government, or a bank must follow these rules like everyone else.
-->

<!-- IMAGES -->
<!-- {{ site.url }} - not needed-->
  [1]: /assets/images/Peeps.png
  [2]: /assets/images/wizardHarry.png
  [3]: /assets/images/enchantedDocuments.png
  [4]: /assets/images/AtoB.png
