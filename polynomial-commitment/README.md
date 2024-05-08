# Polynomial Commitment

KZG10 defines that a polynomial commitment consists of six algorithms: Setup, Commit, Open, VerifyPoly, CreateWitness, and VerifyEval.\
- Setup($1^{\kappa}, t$): to generate an appropriate algebraic structure $\mathcal{G}$ and a commitment key pair $(CK, SK)$. (Commit key $CK$ is a public key and $SK$ is not required in the rest of the scheme. Setup is run by a trusted or distributed authority.)
- Commit($CK,f(x)$): generate a commitment $\mathcal{C}$ to commit to a polnomial $f(x)$ by using public commitment key $CK$. sometimes also output an associated decommitment information $d$(in some constructions, $d$ is null).
- Open($CK, C, f(x), d$): to open the commitment $\mathcal{C}$ and outputs the polynomial with decommitment information $d$.
- VerifyPoly($CK, C, f(x), d$): to verify that the commitment $\mathcal{C}$ is a commitment to the polynomial $f(x)$. If so it output 1, otherwise outputs 0.
- CreateWitness($CK, f(x), i, d$): outputs <$i, f(i), w_i$>, where $w_i$ is a witness for the polynomial $f(x)$ at position $i$.
- VerifyEval($CK, C, i, f(i), w_i$): to verify that $w_i$ is a valid witness for the polynomial $f(x)$ at position $i$.