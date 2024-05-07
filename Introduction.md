# Introduction

> A curated list of awesome commitment schemes.

## What is commitment scheme?

A commitment scheme is a classical cryptographic primitive that allows one to commit to a value while keeping it hidden to others, with the ability to reveal the committed value later. Commitment schemes are used in many cryptographic protocols, including zero-knowledge proofs, secure computation, verifiable delay functions, and many others.

There are two phases in a commitment scheme: the commit phase and the reveal phase.

* In the commit phase, the committer commits to a value `x` by sending a commitment `C` to the receiver.
* In the reveal phase, the committer reveals the committed value `x` to the receiver. The receiver can verify that the revealed value `x` is consistent with the commitment `C` received in the commit phase.

The basic properties of commitment schemes are:

1. **Hiding**: The commitment `C` does not reveal any information about the committed value `x`.
2. **Binding**: The committer cannot change the committed value `x` after the commit phase.

According to the computing power of verifiers or provers, the commitment schemes can be classified into two categories:

1. **Computational commitment schemes**: The hiding property holds against computationally bounded verifiers, and the binding property holds against computationally bounded provers.
2. **Uncomputational commitment schemes**: The hiding property holds against unbounded verifiers, and the binding property holds against unbounded provers.

There are several types of commitment schemes:

* Single-value commitment schemes.
* Cryptographic accumulator.
* Polynomial commitments
* Functional commitment schemes which can be viewed as a generalization of
  * Vector commitments.
  * Matrix commitments.
  * Polynomial commitments.

## Surveys on commitment schemes

* [Commitment Schemes and Zero-Knowledge Protocols(2017)](https://pascholl.github.io/download/ComZK08.pdf)
* [An Overview of Cryptographic Accumulators](https://arxiv.org/pdf/2103.04330.pdf)

## Single-value commitment schemes

### Papers

## Commitment mechanism with one or several certain properties

Those commitment schemes are not necessarily efficient, but they have some nice properties, such as timed commitment, homomorphic commitment, etc.

### Timed commitment

### Papers

* [Timed Commitments](https://www.iacr.org/archive/crypto2000/18800237/18800237.pdf)
