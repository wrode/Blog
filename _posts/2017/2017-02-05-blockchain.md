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

One day, the customers of the bank decide that they do not want the bank to be in charge of maintaining *the* agreement anymore. In fact, they do not want any single authority to maintain the agreement. They decide that anyone can take part in the maintainance of the agreement if they wish. Several people from the crowd accept to take on this role, lets call these participants *peers*. In order to maintain the agreement about who owns what in this new decentralized manner, each peer has their own copy of the paper document with the full agreement - all owners of the currency, their accounts and their corresponding balance. There is no longer one single paper document on which the *true* agreement is written, every peer owns a copy.

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

The rules of the enchanted documents can vary between different sets of documents. //Bitcoin looks a lot like the agreement about a bank, accounts and balances, but as we explore below there are many other different types of agreement.


---

What to write next?

- Could write about:
  - Talk about blockchain enabling programmable money
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
    - Hacks - example, the exchange
    - Why does bitcoin or other cryptocurrencies have value. The cryptocurrecy is just a token.
  - How making a transaction actually looks, using a gif with the update process.

<!--illustration showing documents being updated based on one enchanted document being updated

Should mention that each seperate blockchain needs a way to incentivise the peers to take part in the network. !!Value token.
-->


#### Sato the Wizard

A wizard (lets call him Sato) wants to make a new currency, but he does not want to deal with the hassle of administration. Therefore, he decides to create a set of enchanted documents. He hands out a copy of the enchanted documents to any Peep that wants to own one. The document contains a list of people and their balance of the new currency. Sato enchants the document with the following rule:

    You can send anyone else your own money.
    This is done reducing the balance next to your name and increasing the balance next to the recipient by the corresponding amount.

This rule implicitly states that you cannot increase your own balance, it can only be increased by someone else sending you money. If evil Peep A tries to change the document by increasing his own balance, or reducing the balance of anyone else, the enchantment ensures that the other enchanted documents ignore his updates.

### Back to Blockchains

Blockchains are of course not based on magic, but on a high conceptual level, this simplification is good enough. Blockchains, like sets of enchanted documents, can follow different rules about how to update the agreed upon state.

In the example above, the rules of the enchanted documents create a currency, and the agreement specifies ownership of said currency. In the non-magic world of reality, the most famous example of this type of blockchain is Bitcoin.
<!--mIt is important to note that the only reason Bitcoin has any value, is because people believe that bitcoin is valuable, and are willing to exchange bitcoin for dollars or euros-->

Another set of enchanted documents could be defined by rules about how to handle agreements which are written on the enchanted document. The enchantment would ensure that any agreement written on the enchanted document was upheld. Blockchains with these rules also exists, the most famous of which is called Ethereum. Agreements, written as code, can be uploaded to the blockchain.  In a world of magic, these agreements would ensure that the agreement was upheld in the physical world - not only on the enchanted document. In reality, a blockchain does not yet have any legal precedence outside the blockchain - and so an agreement on a blockchain can only be enforced on the blockchain.

Agreements on the blockchain have been named *Smart Contracts* and deserve a blog post of their own.


<!--
why does it matter...

This also means that there is no central authority who can independently change the rules of the blockchain. The rules are already set in the blockchain, and a government, or a bank must follow these rules like everyone else.
-->

<!-- IMAGES -->
<!-- {{ site.url }} - not needed-->
  [1]: /assets/images/Peeps.png
  [2]: /assets/images/wizardHarry.png
  [3]: /assets/images/enchantedDocuments.png
