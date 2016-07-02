---
layout: post
title: What is a Blockchain?
draft: true
---

<!--more-->

    A Blockchain is a decentralized database that carries out transactions based on a predefined protocol.

There, now you know that. The problem is, if you are like most people this sentence wasn´t very helpful. 

In some circles, Blockchain is so hot right now, it´s the talk of the town. But even though there is a lot of discussion about Blockchain technology, few people actually understand what this thing is. Or more importantly - what it can become.

Most explanations of blockchain are full of IT jargon. So unless you know IT, the explanations don´t really help. In this post I try to explain blockchain without the IT part, and why it is such a big deal.

### Agreement

Agreement is nice. Whether its agreeing about the best football team, what cheese tastes good or which political candidate will make a country great again. If you take a step back and look, different types of agreements exist everywhere. It´s not only the explicit agreements you might have in a conversation. The very fact that you are able to communicate abstract ideas with  another person is based on an agreement about the meaning of the words being spoken.

![Cheese tastes good]({{ site.url }}/assets/images/CheeseTastesGood.jpg)

    more than one agreement here

Different types of agreement have varying degrees of societal consequence. Some subjects are unimportant to reach an agreement about. As an example, it is not very important that you agree with your friend about the best tasting cheese. In this case, you can agree to disagree, and go off eating the cheese that you prefer. Other things are a little more important, say that you are a couple that can only afford to buy one type of cheese. If you don´t agree about what cheese to buy, hard feelings and arguments may pursue. But for society as a whole, agreement here is still not very important. On the other end of the scale there are things which are really important for a society as a whole to agree about in order to function. One such thing is agreeing about language and the meaning of words.

![Consequences for society]({{ site.url }}/assets/images/ConsequencesForSociety.jpg)

For societies to function, there needs to be a common agreement about some of the more important subjects. An obvious place to start, is agreeing about the rules of the society (also known as laws).


#### Agreeing about agreements

One of these laws may be to allow people to enter into bindings agreements with one another. This agreement exists in most modern societies, but it is not without restrictions. People can not enter into *any* binding agreement they wish. The agreement about agreements specifies what is allowed and what is not allowed to enter into binding agreements about.

This rule defines what members of the society *can* make agreements about, and what process to follow if an agreement is not being upheld. Essentially, an agreement about how to handle agreements. Minimum wage is an example of one of these restrictions - you are not allowed to agree to work for an hourly wage which is less than the agreed upon minimum.

The agreement about agreements is know as contract law. Modern societies have a central authority for documenting, updating and enforcing the contract law. This is the legislative branch of the government. If there is a dispute about an agreement, then you can take this agreement to the authority, who in turn chooses what to do about the dispute (aka going to court).


#### Ownership

Another rule is whether people in the society *can* own things at all. This may seem like a no brainer, but its not actually a given, take some of the hippy [communes](https://en.wikipedia.org/wiki/Commune) as an example.

Once you have established the agreement that individuals can own things, the next step is to make sure there is agreement about who owns what. For some things, such as the personal property which I wear - it´s pretty clear. If I make some sandals out of hemp, they are either on my feet or in my apartment. It is also not the end of the world if I happened to lose them. Likewise, it sucks to lose other pieces of clothing, my wallet, my playstation controller etc. But again, it´s not the end of the world, life goes on. 

Then there are the big things. Things that *really* do impact you if you lose them. An example of a big thing is the apartment that you own. Losing that apartment would be life changing. If it was possible to steal an apartment in the same way that you could steal a purse, then that is what thiefs would be doing because that is were the big bucks would be. People would be spending their time protecting their apartment, and society as a whole would not function well. Therefore, it is important that society agrees about who owns the big things.

So what is stopping another person from sneaking in to my apartment and claiming it for himself, while I am strolling about town in my new hemp sandals? 

The problem is that todays societies are so huge that people can´t be expected to keep track of who owns which apartment. You cannot trust individuals to report this themselves, because there is an incentive problem. 

Why would society trust that the apartment is mine when the con artist claiming that the apartment is his is just as credible. In fact, he´s more credible, because he is wearing a suit and I am wearing hemp sandals.

![Who owns the apartment]({{ site.url }}/assets/images/WhosApartment.jpg)

Just like with the agreement about agreements, agreement about ownership is solved in our societies by relying on a single source of "truth" - centrally administrated by a trusted authority.

In the case of apartments, the government owns a central registry of who owns what land. But there are also many other registries which keep track of who owns what (among other things):
- Governments keep track of who owns what veichle registration plates.
- Kennel clubs keep track of who owns what dog through a breed registry.
- The nonprofit organization ICANN keeps track of who owns what internet domain names. 
- A bank keeps an up to date ledger with the balance of account holders.

### Blockchain

Ok, but what does blockchain have to do with agreements?

Blockchain technology is essentially just a new way to reach agreement about the state of something. What's new is that unlike the traditional methods that we mentioned above, the agreement is not administrated (controlled) by a central authority.

Instead of the central authority owning a single document that captures the agreed upon state, everyone who wants to document the agreed upon state is allowed to do so. Let us call the people who wants to take part in documenting the state **Peeps**. 

<!--
    Should have an image of a large amount of people here, with some of them with their hands up in the air. An an arrow signaling that these are the peeps
-->

Ofcourse, the agreed upon state *should* not vary between the Peeps - then there would not be agreement. In order to ensure that all the Peeps had the same document, they would need to meet, dokument the state, and then sign eachothers dokument. This might be fine if the agreement in question did not change. The problem arises when you have an agreement which often changes. If all the Peeps needed to meet, update and sign a new version of the document every time someone makes a bank transaction, this system would be extremely inefficient.

<!--
    The society as a whole would need to agree that most of the peeps were honest

    This might lead just a few people willing to be PEEPS. This would then mean that the whole thing was centralized.
-->

The ability for many Peeps to keep an up-to-date documentation of the agreed upon state is what the Blockchain technology enables. Once you start asking *how* the Blockchain technology does this you start venturing down the rabbit hole and things can get IT jargony very quickly. Fortunately, we can pretend that Blockchains are based on **magic** instead of fancy **technology**.

<!--
    Am I cheating by using magic to get around the promise of not using IT jargon?
-->

![You´re a wizard]({{ site.url }}/assets/images/WizardHarry.png)

Imagine if all the Peeps have a copy of an enchanted document with the agreed upon state. This enchanted document has the following magic properties:

- The documents have a set of magic rules which need to be followed in order to make an update to the agreement.
- If an update is made to one of the enchanted documents and it followed the rules, this update would also be applied to all the other enchanted documents.

The rules of the enchanted documents can vary, it´s these rules that result in many different Blockchain. In the case of a Blockchain that specifies ownership, the magic rule is that only people that have ownership of item A can give away this ownership to someone else. If anyone else have this document

Blockchains are ofcourse not based on magic, but on the conceptual level, this simplification is good enough.

So if you own an apartment, let one of the peers kno

The document is enchanted in such a way that people cannot make changes to the truth unless you are being honest. So that you cannot change the document to say that you own an apartment which you don’t.


<!--
This also means that there is no central authority who can independently change the rules of the blockchain. The rules are already set in the blockchain, and a government, or a bank must follow these rules like everyone else.

Talk about the weak link between the blockchain and the real world. For example, that scarcity of a certain type of token. And this only has value in the real world because people are willing to pay a price for it.

That’s what is meant by decentralized. Instead of one entity managing a central truth for everyone else, now many entities can own an up to date copy of the truth.

Its all about documenting the state of things. One truth which there is agreement about (at least on the societal level)

- Contracts are the things that need to be explicitly defined. When there needs to be agreement.
- Political views, but there is agreement about who can govern even if there is no agreement about who should govern.
- de facto vs de jura - queen in england owning all the land
- contracts are a strange case, because no central authoroty actually keeps this state. But both parties have signed versions of the contract which is presented to a central authority in the case a dispute has to be solved.

- Its worth noting that not everyone might agree with the rules of the society. In fact, they probably dont, but they know the consequences if they do not agree about something.

Another form agreement is social norms, of how you should and should not behave in certain settings.

There are other types of implicit agreements, such as eyeballing the girlfriend of the bulky guy with the tribal tatoo.

- if today you someone had sneaked in your apartment and claimed it fo rthemselves, the first people that the police would check with is probably the neighbours. They likely do have an up to date view about who owns what. And the police trust them to be honest.
    + But you cannot be sure that they have an up to date view of the world. What if the unknown stranger had just paid a large sum of money for the apartment but the old owner still claimed ownership.
    + Agreement is very important in my project. The governance structure is extremely important. It could be made using a smart contract.
- The good thing about smart contract is that everything needs to be so explicitly defined. This means that there is less room missunderstanding.
- Explain that there are private and public blockchains

-documenting isnt really enough, enforcing is also important.

There needs to be some sort of way that society agrees upon who owns what. One single source of the "truth". This is usually solved by one central authority documenting the state of things.
-->