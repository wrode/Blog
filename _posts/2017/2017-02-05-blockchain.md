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

In order to illustrate the difference, let us take a closer look at the agreement relating to the ownership of money, more specifically - the local currency. We'll pretend that banks maintain the agreement about who owns what on a single document. The document consists a list of all the customers, their accounts and their corresponding balances (this is *the agreement*). Every time a customer wants to send some money, they notify the bank, and the bank updates *the agreement* by subtracting some money from one account and adding it to another.

One day, the people in the society decide that they do not want the bank to be in charge of maintaining *the agreement* anymore. In fact, they do not want any single authority to maintain it. They decide that anyone can take part in the maintainance of the agreement if they wish. Several people from the ##crowd accept to take on this role. Let us call the people who participante in maintaining the agreement *peers*. In order to maintain the agreement about who owns what in this new decentralized manner, each peer has their own copy of the paper document with the full agreement, which includes all owners of the currency, their accounts and their corresponding balance. There is no longer one single paper document on which the *true* agreement is written, every peer owns a copy.

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

![Enchanted documents][3]{:.img80}

In the example above, we looked at an agreement about the ownership of a currency. The magic rules of these documents would be:

1. Each enchanted document contains a list of all accounts and their corresponding balances.
2. People own accounts, and can send the balance in their own account to other accounts.

In essence, these rules create a digital cash, the most famous example of which is Bitcoin. Contrary to Bitcoin however, the society in our example suddenly agreed that the local currency would be documented in this new way. The ownership of the local currency would be specified as balances next to the accounts on *the agreement*.

In the real world however, no society maintains their currency in this way. For the agreement named Bitcoin, the balance in each account is only a number which specifies ownership of bitcoins - which has no link to any existing currency.

Yet, we still hear about bitcoins being worth a lot of dollars.

The reason why bitcoins are worth dollars is because people, like you and me, are willing to trade our dollars with bitcoins. We trade our dollars to increase the number next to our accounts in the bitcoin agreement. Just like with traditional currencies, the only reason it has value, is because people believe that it is valuable.

![Bitcoin][5]{:.img35}

The Bitcoin agreement went live in 2009, and the software behind the protocol was made completely open, so anyone could view how the magic really worked. This allowed people to make changes and create copies of the original. These new blockchains are like other sets of enchanted documents that follow different rules regarding how the agreement is updated.

Yet all these other public blockchains share the property of having a list of accounts and balances at their core, so that they have their own blockchain currency - also called their cryptocurrency.

The reason for this is that each blockchain must have a mechanism to reward the peers who maintain the agreement. The peers are renumeranted with the blockchain currency for maintaining the agreement. Without accounts and balances, no blockchain currency exists, and no payment can be made to the peers. Without payment, no incentives exist for the peers to maintain the agreement, which leads to no agreement being maintained.

---

Thinking about bitcoin (and other cryptocurrencies) as a digital version of physical cash can be a little misleading. Whenever you send someone a bitcoin, a bitcoin does not physically move from you to them. Instead, the distributed agreement about the ownership of bitcoin is updated. The balance on your account is reduced, and the balance on the recipients account is increased. The process is presented in the illustration below:

![AtoB][4]{:.img70}

---

One of the first of these copies was Namecoin. In addition to having the standard sets of accounts and balances, the documents of this agreement includes information about websites that you owned.
*write more about namecoin*

In addition to creating blockchains for digital assets, other blockchains for the
Both digital cash and domain names are ownership for digital assets. But blockchains can also be used to track the ownership of physical assets - in these cases of course you will need a lega

Blockchains are obvious use cases for the administration of digital assets, such as a digital cash or a domain name registry, but you can also represent physical assets on the blockchain too. The blockchain itself would not be able to enforce the agreement about ownership. But as long as there is agreement that ownership on the blockchain means ownership in the real world a blockchain could be used for this as well.


<!-- A state -> a snapshot about who owns what at the current moment. Include information that transaction history is maintained.-->

Not only can varying rules of blockchains describe ownership of different types of assets, and how to handle these, the rules of a blockchain can focus on how ownership is updated. One example is that if you can prove to a blockchain that you have stored some data, the blockchain automatically transfers some of the local cryptocurrency to your account. In effect, you are creating an automatic mechanism for paying for distributed storage, creating an airbnb for storage. A Blockchain which is currently doing this is named Siacoin.

The title of airbnb for , because it gives the impression that only people at home would rent out their storage. But what essentially you have created is a very efficient market for the storage for data - completely automated.

Other projects are also in the making in which you would prove to a blockchain that you are creating

Varying blockchain rules describe how the blockchain is updated in different ways. With namecoin it describes the mechanisms to handle domain names.

With siacoin, you essentially have a distributed agreement, with some predefined agreements about how to reward storage of information with the local cryptocurrency. If you want to store something you have to pay, if you store something you will be automatically paid.


Anyone  can define the rules of how the blockchain changes from one state to another -> based on some foundational rules. E.g. the blockchains consititutional rules.

Go on to talk that it is really about programmable ownership.
->
Many different types of applications
->
Enter Ethereum

Another set of enchanted documents could be defined by rules about how to handle agreements which are written on the enchanted document. The enchantment would ensure that any agreement written on the document was upheld. Blockchains with these rules also exists, the most famous of which is called Ethereum. Agreements, written as code, can be uploaded to the blockchain.  In a world of magic, these agreements would ensure that the agreement was upheld in the physical world - not only on the enchanted document. In reality, a blockchain does not yet have any legal precedence outside the blockchain - and so an agreement on a blockchain can only be enforced on the blockchain.

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
  [1]: /assets/images/Peeps.png
  [2]: /assets/images/wizardHarry.png
  [3]: /assets/images/enchantedDocuments.png
  [4]: /assets/images/AtoB.png
  [5]: /assets/images/BitcoinDoc.png
