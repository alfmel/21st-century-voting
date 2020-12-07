# 21st-Century Voting System

If you have additional questions, please select _Issues_ above and open a new issue. We'd love to answer your questions.


## FAQ

**Q**: Why is this project being created?

A: There are several projects in various stages of development, even some considered production-ready. In the authors' opinions, none of them provide the full non-repudiation and integrity protection this project will provide. If, during future analyses, a system is found that meets or can be modified to meet the goals of this project, then focus will shift into one or more of those projects.


**Q**: Is app-based or web-based voting even safe?

A: It most certainly can be if built correctly. That is our goal. We will use multiple [asymmetric cryptographic keys](https://en.wikipedia.org/wiki/Public-key_cryptography) for each individual voter to encrypt and sign voters' ballots. This allows the system to certify, with a very high level of confidence, each ballot cast was cast by the registered voter. It will also allow counting and audit processes to verify every ballot has not been altered in any way.

Asymmetric cryptography (or [public key encryption](https://www.youtube.com/watch?v=AQDCe585Lnc)) is used in TLS/SSL to establish secure communications channels all over the web. This includes e-commerce sites, online banks and communication systems like those used by the U.S. military. It is trusted with billions of private communications and financial transactions every day. If it can protect the highest secrets and billions of dollars very day, then it is capable of protecting democratic elections.


**Q**: Yeah, but online systems are hacked all the time. How can you make the claim this can't be hacked?

A: We are not claiming our voting system can't be _hacked_; we are claiming unauthorized data manipulation (the kind that casts doubt over election results) will be _detectable and identifiable_. This is a huge technological leap over our current systems. Additionally, every voter on mobile devices will be able to verify their vote was received and counted exactly as they cast it.

**Q**: How will you be able to provide voter confidentiality?

A: Cryptographic hashes allow us to digitally fingerprint data. These digital fingerprints are able to uniquely differentiate voters without using or disclosing any personal identifiable information. Each voter, with their own unique digital fingerprint, will be able to find, identify and verify their vote among the thousands cast without disclosing anything else about themselves..


**Q**: Will this project use blockchain?

A: We don't believe blockchain will be necessary. Blockchain is a great technology for distributed ledgers, but forces us to do things that may not add value. We will use one of the central pieces of blockchain: [hash chains](https://en.wikipedia.org/wiki/Hash_chain). Hash chains will ensure votes cannot be added, altered or deleted without leaving a trace.
