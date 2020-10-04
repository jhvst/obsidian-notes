[[Ethereum 2]]

We used the award-winning verification-aware programming language [[Dafny]] to write a formal (functional and logical) specification of each Beacon Chain function, an implementation of each function, and a proof that the implementation conforms to its specification.

What about the soundness of the verification engine?
You might be wondering, “what if the Dafny compiler/verifier is buggy?” We actually know Dafny is buggy (dafny repo issues), but we do not rely on the absence of bugs in Dafny. We rely on Dafny (and its verification engine) to be sound. [[Soundness]] means that when Dafny reports that proofs are correct, they are indeed correct. 

Formally Verifying the Ethereum 2.0 Phase 0 Specifications https://consensys.net/blog/blockchain-development/formally-verifying-the-ethereum-2-0-phase-0-specifications/ by Franck CassezAugust 10, [[2020]]
