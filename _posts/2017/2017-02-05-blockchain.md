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

In order to illustrate the difference, let us take a closer look at the agreement relating to the ownership of money (the local currency). We'll pretend that banks maintain the agreement about who owns what on a single document. The document consists a list of all the customers, their accounts and their corresponding balances (this is *the agreement*). Every time a customer wants to send some money, they notify the bank, and the bank updates *the agreement* by subtracting some money from one account and adding it to another.

One day, the people in the society decide that they do not want the bank to be in charge of maintaining *the agreement* anymore. In fact, they do not want any single authority to maintain it. They decide that anyone can take part in the maintainance of the agreement if they wish. Several people from the society accept to take on this role. Let us call the people who participante in maintaining the agreement *peers*.

In order to maintain the agreement about who owns what in this new decentralized manner, each peer has their own copy of the paper document with the full agreement, which includes all owners of the currency, their accounts and their corresponding balance. There is no longer one single paper document on which the *true* agreement is written, every peer owns a copy.

![Peers][1]{:.img90}

Whenever there is a change in the agreement, i.e. every time a transaction is made, all the peers will need to update their agreement - since of course, the agreement should not vary between the peers. In order to ensure that all the peers have the same agreement documented, they would need to meet, agree upon the update, update the agreement, and then sign each others document.

For other types of agreements this manual process of update might be fine. Especially if the agreement in question did not change, or if it only changed once every 10 years. The problem arises when you have an agreement which often changes. If all the peers needed to meet, update and sign a new version of the document every time someone makes a bank transaction, this system would be extremely inefficient.

Blockchain to the rescue! Blockchain technology enables peers to efficiently maintain an up-to-date agreement. Once you start asking *how* Blockchain technology does this you start venturing down the rabbit hole and things can get IT jargony very quickly. Fortunately, we can pretend that Blockchains are based on magic instead of fancy technology.

![You're a wizard][2]{:.img70}

Using the magic analogy, a public blockchain can be imagined the following way:
- An identical agreement is written on a set of enchanted documents
- Anyone can take part in maintaining this agreement by owning one of these documents
- Rules describe the changes you are allowed to make to a document
- Any valid change to one document is automatically made to all the other documents

These magic properties ensure that all the peers have an identical and up-to-date copy of the agreement. There is no central authority which controls the definitive agreement, all the peers own a copy. This is why Blockchains are referred to as decentralized; there is no central controller of the true agreement.

![Enchanted documents][3]{:.img80}

In our example, we looked at an agreement about the ownership of a currency. The magic rules of these documents would be:

1. Each enchanted document contains a list of all accounts and their corresponding balances.
2. People own accounts, and can send the balance in their own account to other accounts.

In essence, these rules create a digital cash, the most famous example of which is Bitcoin. Contrary to Bitcoin however, the society in our example suddenly agreed that the local currency would be documented in this new way. The ownership of the local currency would be specified as balances next to the accounts on *the agreement*.

In the real world however, no society maintains their currency in this way. For the agreement named Bitcoin, the balance in each account is only a number. There is no explicit agreement that this number should be worth anything at all, unlike normal currencies which members of modern societies are legally required to accept as payment.

Yet, we still hear about bitcoins being worth a lot of money. At the time of writing, a bitcoin is trading for over $2000. Why?

Bitcoins have value because people, like you and me, are willing to trade our dollars with bitcoins. We trade our dollars to increase the number next to our accounts in the bitcoin agreement. Just like with traditional currencies, the only real reason it has value, is because people believe that it is valuable.

![Bitcoin][5]{:.img35}

The Bitcoin agreement went live in 2009, and the software behind the protocol was made completely open, so anyone could view how the magic really worked. This allowed people to make changes and create copies of the original. In terms of our magic analogy, these new derivative blockchains are like other sets of enchanted documents. These new sets of documents can follow different rules for how the agreement is updated.

Even though the rules of these other blockchains vary, they still share the property of having a list of accounts and balances at their core, so that they have their own blockchain currency (aka cryptocurrency). Every public blockchain needs a cryptocurrency, in order to be able to rewards the peers who maintain the agreement.

---

Thinking about bitcoin (and other cryptocurrencies) as a digital version of physical cash can be a little misleading. Whenever you send someone a bitcoin, a bitcoin does not physically move from you to them. Instead, the distributed agreement about the ownership of bitcoin is updated. The balance on your account is reduced, and the balance on the recipients account is increased. The process is presented in the illustration below:

![AtoB][4]{:.img70}

---

One of the first imagined alternative uses for blockchains was the maintainance of website ownership. Instead of this being managed centrally, the rules governing ownership of websites can instead be maintained on a blockchain.

In addition to creating blockchains for the agreement about digital assets such as digital cash or websites, you can also represent physical assets on a blockchain. The blockchain agreement could describe who owns what commodities, real estate, financial instruments and even existing currencies. The blockchain itself does not have any power outside its own agreement, it can't break someones legs if the physical gold represented on the blockchain isn't accounted for. But it is still possible to use Blockchains as the way of maintaining these agreements if the agreement is given legal precedence or a trusted third party "backs" it.

Not only does a blockchain agreement describe ownership of varying types of assets, the rules of a blockchain also define *how* this ownership is governed.
- For the ownership of websites, these rules would define how the websites are first aquired through auctions, how ownership is transfered and rules to stop people from squatting on the websites.
- For a blockchain where the ownership of company shares is maintained, these rules could specify how dividends are paid to the owners of shares, how these owners vote, and how the ownership is transferred.
- Another blockchain has some rules for payment if certain conditions are met. If you store some data for an amount of time and you prove it to that blockchain, then the blockchain can automatically make you a payment for storing the data.

All of the above examples describe blockchains with varying rules for *how* the agreement is updated. These rules can also be thought of as agreements, more specifically - they are predefined agreements about how the agreement is updated.

Eventually, as more people started thinking about different blockchain applications, it became clear that a more general purpose blockchain would make sense - a blockchain which did not update its agreement solely based on predefined agreements, but one on which anyone could make new agreements about how to update the state (given that they follow some basic rules).

These agreements about how to update the blockchain agreement are better known as smart contracts, and will be the focus of the next post in this series.

---
If you liked the article, you can tip me some ether or tokens at the following address:
0xAEe32096745dbf51362E2984fC0fFb78d7a47f47

<!-- IMAGES -->
  [1]: /assets/images/Peers.png
  [2]: /assets/images/wizardHarry.png
  [3]: /assets/images/enchantedDocuments.png
  [4]: /assets/images/AtoB.png
  [5]: /assets/images/BitcoinDoc.png
