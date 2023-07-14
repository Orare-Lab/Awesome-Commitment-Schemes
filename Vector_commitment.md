# Vector Commitment Scheme
Vector commitment is a short commitment to an ordered sequencer of values, which support to open the commitment at specific positions with small proof without opening the whole vector. Therefore, the vector commitment should satisifies the property: **position binding**.
The ubiquitous example of vector commitment is Merkle tree.

The property of Vector commitment schemes:
1. Position binding: The commitment is binding to the position of the opened value.
2. Efficiently aggregatable: combination of commitments is efficient.
3. maintainable: The commitment can be updated efficiently, which means updating all proofs in sublinear time.

## Hyperproof
Hyperproof is a vector commitment scheme based on the discrete log assumption. It is a generalization of Merkle tree, which can be used to prove the correctness of the execution of a program on a large dataset. The proof size is logarithmic in the size of the dataset.

## Papers

- [Hyperproof](https://eprint.iacr.org/2021/599.pdf)
- [Matproof](https://dl.acm.org/doi/pdf/10.1145/3548606.3560591)