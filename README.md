# Awesome-commitment-schemes

> A curated list of awesome commitment schemes.

A commitment scheme is a classical cryptographic primitive that allows one to commit to a value while keeping it hidden to others, with the ability to reveal the committed value later. Commitment schemes are used in many cryptographic protocols, including zero-knowledge proofs, secure computation, verifiable delay functions, and many others.

There are two phases in a commitment scheme: the commit phase and the reveal phase. 
- In the commit phase, the committer commits to a value `x` by sending a commitment `C` to the receiver. 
- In the reveal phase, the committer reveals the committed value `x` to the receiver. The receiver can verify that the revealed value `x` is consistent with the commitment `C` received in the commit phase.

And there are several types of commitment schemes:
- Single-value commitment schemes
- Functional commitment schemes which can be viewed as a generalization of 
  - Vector commitments.
  - Matrix commitments.
  - Polynomial commitments.


## Surveys on commitment schemes

- [Commitment Schemes and Zero-Knowledge Protocols(2017)](https://pascholl.github.io/download/ComZK08.pdf)

## Single-value commitment schemes

### Papers

### Implementations


## Funtional commitment schemes

### papers

- [Functional Commitment Schemes: From Polynomial Commitments to Pairing-Based Accumulators from Simple Assumptions](https://eprint.iacr.org/2016/766)
- [Efficient Functional Commitments: How to Commit to a Private Function](https://eprint.iacr.org/2021/1342)
- [Functional Commitments for All Functions, with Transparent Setup and from SIS](https://eprint.iacr.org/2022/1368)
- [Succinct Vector, Polynomial, and Functional Commitments from Lattices](https://eprint.iacr.org/2022/1515)


##  Commitment mechanism with one or several certain properties


Those commitment schemes are not necessarily efficient, but they have some nice properties, such as timed commitment, homomorphic commitment, etc.
### Timed commitment

### Papers
- [Timed Commitments](https://www.iacr.org/archive/crypto2000/18800237/18800237.pdf)