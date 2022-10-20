## Complexity-Theory

### I Basic Complexity Classes

- **1. The computational model —and why it doesn’t matter**
  - 1.1 Encodings and Languages: Some conventions
    - 1.1.1 Representing objects as strings
    - 1.1.2 Decision problems / languages
    - 1.1.3 Big-Oh notation
  - 1.2 Modeling computation and efficiency
    - 1.2.1 The Turing Machine
    - 1.2.2 Robustness of our definition
    - 1.2.3 The expressive power of Turing machines
  - 1.3 Machines as strings and the universal Turing machines
    - 1.3.1 The Universal Turing Machine
  - 1.4 Uncomputable functions
    - 1.4.1 The Halting Problem
  - 1.5 Deterministic time and the class **P**
    - 1.5.1 On the philosophical importance of **P**
    - 1.5.2 Criticisms of **P** and some efforts to address them
    - 1.5.3 Edmonds’ quote
  - Chapter notes and history
  - Exercises
  - 1.A Proof of Theorem 1.13: Universal Simulation in O(T log T)-time
- **2. NP and NP completeness**
  - 2.1 The class **NP**
    - 2.1.1 Relation between **NP** and **P**
    - 2.1.2 Non-deterministic Turing machines
  - 2.2 Reducibility and NP-completeness
  - 2.3 The Cook-Levin Theorem: Computation is Local
    - 2.3.1 Boolean formulae and the CNF form
    - 2.3.2 The Cook-Levin Theorem
    - 2.3.3 Warmup: Expressiveness of boolean formulae
    - 2.3.4 Proof of Lemma 2.12
    - 2.3.5 Reducing SAT to 3SAT
    - 2.3.6 More thoughts on the Cook-Levin theorem
  - 2.4 The web of reductions
    - 2.4.1 In praise of reductions
    - 2.4.2 Coping with **NP** hardness
  - 2.5 Decision versus search
  - 2.6 **coNP**, **EXP** and **NEXP**
    - 2.6.1 **coNP**
    - 2.6.2 **EXP** and **NEXP**
  - 2.7 More thoughts about **P**, **NP**, and all that
    - 2.7.1 The philosophical importance of **NP**
    - 2.7.2 NP and mathematical proofs
    - 2.7.3 What if **P** = **NP**?
    - 2.7.4 What if **NP** = **coNP**?
  - Chapter notes and history
  - Exercises
- **3. Diagonalization**
  - 3.1 Time Hierarchy Theorem
  - 3.2 Space Hierarchy Theorem
  - 3.3 Nondeterministic Time Hierarchy Theorem
  - 3.4 Ladner’s Theorem: Existence of NP-intermediate problems
  - 3.5 Oracle machines and the limits of diagonalization?
  - Chapter notes and history
  - Exercises
- **4. Space complexity**
  - 4.1 Configuration graphs
  - 4.2 Some space complexity classes
  - 4.3 PSPACE completeness
    - 4.3.1 Savitch’s theorem
    - 4.3.2 The essence of PSPACE: optimum strategies for game-playing
  - 4.4 NL completeness
    - 4.4.1 Certificate definition of NL: read-once certificates
    - 4.4.2 **NL** = **coNL**
  - Chapter notes and history
  - Exercises
- **5. The Polynomial Hierarchy and Alternations**
  - 5.1 The classes **Σ(^p)(_2)** and **Π(^p)(_2)**
  - 5.2 The polynomial hierarchy
    - 5.2.1 Properties of the polynomial hierarchy
    - 5.2.2 Complete problems for levels of **PH**
  - 5.3 Alternating Turing machines
    - 5.3.1 Unlimited number of alternations?
  - 5.4 Time versus alternations: time-space tradeoffs for SAT
  - 5.5 Defining the hierarchy via oracle machines
  - Chapter notes and history
  - Exercises
- **6. Circuits**
  - 6.1 Boolean circuits
    - 6.1.1 Turing machines that take advice
  - 6.2 Karp-Lipton Theorem
  - 6.3 Circuit lowerbounds
  - 6.4 Non-uniform hierarchy theorem
  - 6.5 Finer gradations among circuit classes
    - 6.5.1 Parallel computation and NC
    - 6.5.2 P-completeness
  - 6.6 Circuits of exponential size
  - 6.7 Circuit Satisfiability and an alternative proof of the Cook-Levin Theorem
  - Chapter notes and history
  - Exercises
- **7. Randomized Computation**
  - 7.1 Probabilistic Turing machines
  - 7.2 Some examples of PTMs
    - 7.2.1 Probabilistic Primality Testing
    - 7.2.2 Polynomial identity testing
    - 7.2.3 Testing for perfect matching in a bipartite graph
  - 7.3 One-sided and zero-sided error: **RP**, **coRP**, **ZPP**
  - 7.4 The robustness of our definitions
    - 7.4.1 Role of precise constants, error reduction
    - 7.4.2 Expected running time versus worst-case running time
    - 7.4.3 Allowing more general random choices than a fair random coin
  - 7.5 Randomness efficient error reduction
  - 7.6 **BPP** ⊆ **P**/poly
  - 7.7 **BPP** is in **PH**
  - 7.8 State of our knowledge about **BPP**
    - 7.8.1 Complete problems for **BPP**?
    - 7.8.2 Does **BPTIME** have a hierarchy theorem?
  - 7.9 Randomized reductions
  - 7.10 Randomized space-bounded computation
  - Chapter notes and history
  - Exercises
  - 7.A Random walks and eigenvalues
    - 7.A.1 Distributions as vectors and the parameter λ(G)
    - 7.A.2 Analysis of the randomized algorithm for undirected connectivity
  - 7.B Expander graphs
    - 7.B.1 The Algebraic Definition
    - 7.B.2 Combinatorial expansion and existence of expanders
    - 7.B.3 Error reduction using expanders
- **8. Interactive proofs**
  - 8.1 Warmup: Interactive proofs with a deterministic verifier
  - 8.2 The class **IP**
  - 8.3 Proving that graphs are not isomorphic
  - 8.4 Public coins and **AM**
    - 8.4.1 Set Lower Bound Protocol
      - Tool: Pairwise independent hash functions
      - The lower-bound protocol
    - 8.4.2 Some properties of **IP** and **AM**
    - 8.4.3 Can GI be **NP**-complete?
  - 8.5 **IP** = **PSPACE**
    - 8.5.1 Arithmetization
    - 8.5.2 Interactive protocol for #SATD
      - Sumcheck protocol
    - 8.5.3 Protocol for TQBF: proof of Theorem 8.17
  - 8.6 The power of the prover
  - 8.7 Program Checking
    - 8.7.1 Languages that have checkers
  - 8.8 Multiprover interactive proofs (**MIP**)
  - Chapter notes and history
  - Exercises
  - 8.A Interactive proof for the Permanent
    - 8.A.1 The protocol
- **9. Complexity of counting**
  - 9.1 The class #**P**
    - 9.1.1 The class **PP**: decision-problem analog for #**P**
  - 9.2 #**P** completeness
    - 9.2.1 Permanent and Valiant’s Theorem
    - 9.2.2 Approximate solutions to **#P** problems
  - 9.3 Toda’s Theorem: **PH** ⊆ **P**^#SAT
    - 9.3.1 The class ⊕**P** and hardness of satisfiability with unique solutions
      - Proof of Theorem 9.15
    - 9.3.2 Step 1: Randomized reduction from **PH** to ⊕**P**
    - 9.3.3 Step 2: Making the reduction deterministic
  - 9.4 Open Problems
  - Chapter notes and history
  - Exercises
- **10. Cryptography**
  - 10.1 Hard-on-average problems and one-way functions
    - 10.1.1 Discussion of the definition of one-way function
    - 10.1.2 Random self-reducibility
  - 10.2 What is a random-enough string?
    - 10.2.1 Blum-Micali and Yao definitions
    - 10.2.2 Equivalence of the two definitions
  - 10.3 One-way functions and pseudorandom number generators
    - 10.3.1 Goldreich-Levin hardcore bit
    - 10.3.2 Pseudorandom number generation
  - 10.4 Applications
    - 10.4.1 Pseudorandom functions
    - 10.4.2 Private-key encryption: definition of security
    - 10.4.3 Derandomization
    - 10.4.4 Tossing coins over the phone and bit commitment
    - 10.4.5 Secure multiparty computations
    - 10.4.6 Lowerbounds for machine learning
  - 10.5 Recent developments
  - Chapter notes and history
  - Exercises

### II Lowerbounds for Concrete Computational Models

- **11. Decision Trees**
  - 11.1 Certificate Complexity
  - 11.2 Randomized Decision Trees 
  - 11.3 Lowerbounds on Randomized Complexity
  - 11.4 Some techniques for decision tree lowerbounds
  - 11.5 Comparison trees and sorting lowerbounds
  - 11.6 Yao’s MinMax Lemma
  - Exercises
  - Chapter notes and history
- **12. Communication Complexity**
  - 12.1 Definition
  - 12.2 Lowerbound methods
    - 12.2.1 Fooling set
    - 12.2.2 The tiling lowerbound
    - 12.2.3 Rank lowerbound
    - 12.2.4 Discrepancy
      - A technique for upperbounding the discrepancy
    - 12.2.5 Comparison of the lowerbound methods
  - 12.3 Multiparty communication complexity
    - Discrepancy-based lowerbound
  - 12.4 Probabilistic Communication Complexity
  - 12.5 Overview of other communication models
  - 12.6 Applications of communication complexity
  - Exercises
  - Chapter notes and history
















