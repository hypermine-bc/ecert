# ecert
Decentralised educational certificate management system

## Credit and references 

The idea is taken from this blog: https://medium.com/mit-media-lab/certificates-reputation-and-the-blockchain-aee03622426f

## We need certifications

When we lived in small tight-knit communities, people knew whom they could turn to when they needed an expert. However, as we started moving around more and our lives and networks grew, we needed to come up with portable ways to signal our expertise to new acquaintances. 

For example, in Germany many carpenters still do an apprenticeship tour that lasts no less than three years and one day. They carry a small book in which they collect stamps and references from the master carpenters with whom they work along the way. The carpenter’s traditional (and now hipster) outfit, the book of stamps they carry, and — if all goes well — the certificate of acceptance into the carpenter guild are proof that here is a man or woman you can trust to build your house.

The trail of credentials and achievements that we generate throughout our lives says something about who we are, and it can open doors that allow us to become who we want to be. Some credentials, such as university degrees, are more important than others. But at the end of the day, all of these credentials represent experiences that are part of our lives.

## Physical certification system

One good thing about the physical certification system is, the user have full control of his physical certificate, like how and where he use them. For example in the above example, a apprentice can carry all of his certificates in his bag and can decied with whome he wants to share with. 

### Problem with physical certification system

When certification systems are not working well, the consequences can be more than just inefficient, such as the cumbersome and expensive process of requesting a university transcript: they can be disastrous, such as when a refugee is unable to provide a certificate of completed study, and is therefore prevented from continuing her education. Digital systems could help in both of these situations.

## Digital certification system

- Making certificates transferable and more easily verifiable is one advantage of digital systems.

### Problem with digital certification system

- Ideally we should be in charge of our own credentials, but most of the time we have to rely on third parties, such as universities or employers to store, verify, and validate our credentials.
- Job seekers have to request official transcripts from their alma maters (and typically pay a small fee), and employers still need to call the university if they want to be sure that a transcript wasn’t faked.
- It’s a slow and complicated process, which is one reason why degree [fraud is a real issue](https://www.nytimes.com/2007/04/27/us/27mit.html).
- fake certification
- counterfeiting in certifications

## We need control of our own credentials

There are many advantages for recipients to have more control over the certificates they earn. Being in control doesn’t mean it would be easy to lie. Similar to the carpenter’s book of references, it should not be possible to just rip out a few pages without anyone noticing. But being in control means having a way to save credentials, to carry them around with us, and to share them with an employer if we chose to do so (without having to pay, or ask for the issuer’s permission or cooperation).

## Need of Blockchain technology for building such system

Using the blockchain and strong cryptography, it is now possible to create a certification infrastructure that puts us in control of the full record of our achievements and accomplishments. It will allow us to share a digital degree with an employer while giving the employer complete trust that the degree was in fact issued to the person presenting it.

The blockchain is best known for its connection to the cryptocurrency bitcoin. But in essence it is a just a distributed ledger to record transactions. What makes it special is that it is durable, time-stamped, transparent, and decentralized. Those characteristics are equally useful for managing financial transactions, as for a system of reputation. In fact you can think of reputation as a type of currency for social capital, rather than financial capital.

## Actors

- **Certificate schema (CS)**: describes the data standard for digital certificates. - [open badges specification ](https://www.imsglobal.org/sites/default/files/Badges/OBv2p0Final/index.html)
- **Certificate issuer (CI)**: issues a certificate by broadcasting a transaction from the issuing institution’s address to a recipient’s address with the hash embedded
- **Certificate verifier (CV)**: used to display and verify digital certificates after they have been issued.

## How it works

- CI create a digital file (CS) that contains some basic information such as the name of the recipient, the name of the issuer, an issue date, etc. 
- CI then sign the contents of the certificate using a private key, and append that signature to the certificate itself. 
- CI create a hash use his private key again to create a record on the blockchain -  that states he issued a certain certificate to a certain person on a certain date. 
- It possible to verify (by CV) who a certificate was issued to, by whom, and validate the content of the certificate itself.

## Advantages

- independence: the student owns and control the credentials
- ownership: the recipient can prove ownership of the credential without the need of a 3rd party;
- control: the recipient has control sharing, distribution, and deletion of the credential
- verifiability: the credential is verifiable on the blockchain without the need for third parties, like employers, admissions committees, and verification organisations;
- permanence: the credential is a permanent record on the blockchain


## References

- https://medium.com/mit-media-lab/what-we-learned-from-designing-an-academic-certificates-system-on-the-blockchain-34ba5874f196
- http://jcreview.com/fulltext/197-1583403182.pdf?1584339148
- https://www.blockcerts.org/
- https://peerj.com/articles/cs-266.pdf
- http://certificates.media.mit.edu/
- https://blockeducate.com/services/blockchain-for-education/#:~:text=Issued%20Blockchain%2Dbased%20academic%20certificates,no%20single%20point%20of%20failure
- https://wiki.mozilla.org/images/b/b1/OpenBadges-Working-Paper_092011.pdf
- https://www.imsglobal.org/sites/default/files/Badges/OBv2p0Final/index.html
