## Course: Blockchain A-Z: Learn How To Build Your First Blockchain
On [Udemy](https://www.udemy.com/course/build-your-blockchain-az/)

I take this course to get familiar with the basics of blockchain technology.

### Schedule

Based on the outlook, I expect to learn about:
- the history of blockchain
- its promising advantages (and disadvantages)
- cryptography theory (e.g. SHA256)
- crypto-currency
- building a blockchain
- building a cryptocurrency
- smart contracts
- developing smart contracts

### Learnings

#### History of Blockchain
09.01.2021 - The common consensus about the origin of the "blockchain" is attributed to Satoshi Nakamoto for his paper on [Bitcoin](https://bitcoin.org/bitcoin.pdf). The underlying cryptographic dynamics of the blockchain, i.e. of linked data blocks, already date back to 1991 by works of Stuart Haber and W. Scott Stornetta.

#### SHA256
09.01.2021 - SHA256 is a cryptographic hash function used to generate a unique hash value for a given string of data. It can be thought of as a fingerprint of any given document or fraction of data. The hash value consists of a 256 bit value of hexadecimal characters. SHA256 was developed by the NSA and is since then used worldwide for digital signatures.

SHA256 is only one of many cryptographic hash functions. SHA256 is widely used as its strong implementation of (security) requirements of a hash function:
- it is a one-way function: It is impossible to derive the original data from its encrypted hash value. 
- it is deterministic: For the same data, it will always produces the same output.
- it is fast: The computation of the hash value is fast enough to be implemented in a large variety of computations without causing a noticeable slowdown.
- it implementes the Avalance effect: Tiny changes in the input data will cause a significant change in the output. This is of particular relevance for security, as similarity in hash values can not be used to infer similarities in the input data.
- it is collision resistant: The probability of a collision of two same hash values for two different inputs is extremely low (1 in 60 million). A collision is a security threat as a document with the same hash value could potentially be replaced with malicious data or with manipulated data without a cryptographic security system in place to detect the change. This probability of collision is low enough to be accepted as a reasonable security level for a hash function.