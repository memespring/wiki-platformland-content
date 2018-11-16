<!-- TITLE: Digital Proof -->

# Digital proof

How do people prove facts about themselves?

Generally, it is still with paper: a birth certificate or a passport; a bank letter or a form with an official stamp on it. Sometimes that piece of paper will list a reference number that allows officials to check the equivalent record in a database, and compare it to the information on the form. Sometimes, it’s just the piece of paper that is trusted.

There are obvious downsides of this:

* As digital printers have become ubiquitous, forgery has become easier (although anti-forgery features, secure printing, distribution and supply of documents can mitigate this risk)

* More information may be shared with than is necessary for the task the holder is trying to complete -- for example, using a driving licence to prove entitlement to drink alcohol may reveal someone’s date of birth and address
* Printing and posting paper documents takes time, and that makes it harder to design services that respond in real-time
High-value, hard to replace documents like passports or birth certificates get used for trivial purposes, like checking in to a hotel

But there are benefits:

* People can prove things to whoever they like and however they like: the designers of a service don’t need to guess up-front all the different situations that someone might experience
* People can prove to one part of government that another part of government agrees a certain fact about them -- for example, that they own a property -- without the need for duplicating and sharing entire datasets between organisations.
* Paper certificates and cards are tangible things -- real-world representations of a service or entitlement
* It’s up to the organisation or individual receiving the proof to decide if they trust it or not, which allows for flexibility
* Digital proofs, of various types, offer the opportunity to keep some of the good things about paper, while removing some of the risks.

## One-use check-codes

One example is the approach used by the GOV.UK ‘Share driving licence’ service. It lets users create a one-use code that a third party (for example a car-rental company) can use to check the details of a licence [^1]. This has the advantage that it clearly puts the user in control of how and when they share data about themselves.

## Digitally signed facts

Digilocker, part of the IndiaStack project, is a personal datastore for cryptographically signed government documents. For example, users can use it to store a digital representation of their driving licence, signed by the government. As technologist Terence Eden has written, there are many situations where it might be useful for official organisations (government departments, universities, courts, etc) to sign facts, for example, that an individual has a particular qualification or is over 18, or that an organisation has a licence to sell a particular medicine. He also points out that this can be done without a blockchain in sight.[^2]

## APIs that answer questions

Rather than sharing a full database record about someone, it is possible to design APIs that answer specific questions. For example, ‘does this car have a permit to park in this area -- yes or no?’ ‘Is this person entitled to work in this country -- yes or no?’
This allows the public to prove facts about themselves, but also one part of government to ask a question of another part, without all the negatives that come with traditional approaches to ‘data-sharing’ in government.

## A replacement for paper?

There is no reason some of these digital proofs could not have a printed representation, much as paper wallets are used for storing bitcoin offline.

## To do

* What Public Key Infrastructure should governments have in place for signing and sharing data?
* What are the situations where zero-knowledge proofs have a role to play?[^3]
* What are the options for new open standards for digital proofs? For example, the w3c Working Group on Verifiable Claims is one such initiative[^4].
* Digital proofs in the real-world e.g. food safety ratings 

Footnotes:

[^1]: . View or share your driving licence information https://www.gov.uk/view-driving-licence
[^2]: Things For Which Cryptographic Signing Would Be Useful. (2018, May 27) https://shkspr.mobi/blog/2018/05/things-for-which-cryptographic-signing-would-be-useful/
Ankur Shah Delight. (2017, June 22). Zero Knowledge Proof of Age Using Hash Chains. Retrieved October 21, 2018, from http://blog.stratumn.com/zkp-hash-chains/
[^3]: Zero Knowledge Proofs: An illustrated primer. (2014, November 27) https://blog.cryptographyengineering.com/2014/11/27/zero-knowledge-proofs-illustrated-primer/
[^4]: Verifiable Claims Data Model and Representations. (2017, August 3) https://www.w3.org/TR/verifiable-claims-data-model/



