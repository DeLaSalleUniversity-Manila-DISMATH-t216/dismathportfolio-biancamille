# My DISMATH Portfolio
dismathportfolio-biancamille created by Classroom for GitHub

## Week 1:
- From our orientation, I learned that the topics to be discussed are not easy.
- I learned that I need to study hard on this subject to pass, even though I have lots of major subjects this term.
- I learned what **Proposition** means and how you could tell that the statement is a proposition or not.
- I learned that this subject deals with **Mathematical Truth**.
- I learned the symbols in logical connectives and the way how to prove it using the truth table.

| Logical Symbol  |  Logical Operator | Shorthand | Formula | Logical Expression |
| :-----: |:-------:|:-----:| :-------: | :-------: |
| ¬ |Negation | not | val(¬p) = 1 - val(p) | ¬p |
| ∧ | Conjunction | and | val(p ∧ q) = min(val(p), val(q)) | p ∧ q |
| ∨ | Disjunction | or | val(p v q) = max(val(p), val(q)) | p v q |
| ⊕ | Exclusive disjunction | xor | if val(p)  not equal val(q) = 1 , otherwise  0|  p ⊕ q  ≡ (¬p ∧ q) v (p ∧ ¬q) |
| → | Conditional | if, then | if val(p)  ≤ val(q) = 1 , otherwise  0  | p → q ≡  ¬p v q |
| ↔ | Biconditional | iff | if val(p) equals val(q) = 1 , otherwise  0 |  p ↔ q ≡ (p → q) ∧ (q → p) |

- I did an advanced reading on "Logical Equivalences and Proof by Truth Table", so I learned the different logical equivalences to use in proving.

| Name |||
| :-----: |:-------:|:-----:|
| Identity Laws | p ∨ F ≡ p | p ∧ T ≡ p |
| Domination Laws| p ∨ T ≡ T | p ∧ F ≡ F |
| Negation Laws| p ∧ ¬p ≡ F | p ∨ ¬p ≡ T |                                            
| Double Negation Laws | (¬(¬p) ≡ p) |                                                           
| Idempotent Laws| p ∨ p ≡ p | p ∧ p ≡ p |                                              
| Commutative Laws | p ∨ q ≡ q ∨ p | p ∧ q ≡ q ∧ p |                                       
| Associative Laws | (p ∨ q) ∨ r ≡ p ∨ (q ∨ r) | (p ∧ q) ∧ r ≡ p ∧ (q ∧ r) |            
| Distributive Laws | p ∨ (q ∧ r) ≡ (p ∨ q) ∧ (p ∨ r) | p ∧ (q ∨ r) ≡ (p ∧ q) ∨ (p ∧ r) |  
| De Morgan's Laws| ¬(p ∧ q) ≡ ¬p ∨ ¬q | ¬(p ∨ q) ≡ ¬p ∧ ¬q |                        
| Absorption Laws | p ∨ (p ∧ q) ≡ p | p ∧ (p ∨ q) ≡ p |                              

- I read the "Rules of Inference" and I got so confused but I already have an idea how it works so maybe I'll just wait for the time that this will be discussed.
- I tried to answer the drills and I find it interesting because it challenges my brain to work.

## Week 2:
- I learned that the Truth Table for Biconditional  is just the negation of Exclusive OR (XOR).

TRUTH TABLE FOR BICONDITIONAL

| p | q | p ↔ q |
| :---: | :---: | :---: |
| 0 | 0 | 1 |
| 0 | 1 | 0 |
| 1 | 0 | 0 |
| 1 | 1 | 1 |

TRUTH TABLE FOR NEGATION OF EXCLUSIVE OR

| p | q | p ⊕ q | ¬ ( p ⊕ q )|
| :---: | :---: | :---: | :---: | 
| 0 | 0 | 0 | 1 |
| 0 | 1 | 1 | 0 |
| 1 | 0 | 1 | 0 |
| 1 | 1 | 0 | 1 |

- I learned the following inverse, converse, and contrapositive of p → q:
  - Inverse: ¬p → ¬q
  - Converse: q → p
  - Contrapositive: ¬q → ¬p
- An implication A → B ≡ ¬A ∨ B
- I learned the proper way of proving certain problem that only uses Logical Equivalences, by identifying what law was applied per step.
- If there's a problem that i need to evaluate, any tools can be used and it will come up to the same answer. For example: Evaluate (p ∧ q) → (p ∨ q). It will come up to the same answer **T** when we use Truth Table or Logical Equivalences - *Implication Equivalence*.
- I learned that Tautology is always true in every possible interpretation.
- I learned that in Universal Quantifier (**∀ x P(x)**), a substitution is not possible for that to be true, rather, the Predicate **P(x) is true for every x**.
- The logical expresion for Universal Quantifier is (P1 ∧ P2 ∧ P3 ∧ ... ∧ Pn) while for Existential Quantifier (P1 ∨ P2 ∨ P3 ∨ ... ∨ Pn).
- I learned that it is easy to prove Existential Quantifier but hard to disprove, opposite with the Universal Quantifier wherein it is easy to disprove it but hard to prove that it is true for instances that are all true.
- I learned that if I want the Universal Quantifier and Existential Quantifier to be false, I will negate them and use the rule of De Morgan by distributing the negation (¬) to their logical expressions.
- In summary, I learned that the **negation of the Universal Statement is the Existential Statement** while the **negation of the Existential Statement is the Universal Statement**.

## Week 3:
- The learned that the Rules of Inference is used to prove for a sequence of statements that would end up with a conclusion.
- I learned that the conclusion must follow from the truth of the preceding statements, or what we call the **premises**, of the argument.
- I learned that whenever all its premises are true, the conclusion must also be true, in other words we call it the **Tautology**.

RULES OF INFERENCE TABLE

| Tautology | Name |
| :-----------: | :------------: |
| (p ∧ (p → q)) → q | Modus Ponens |
| (¬q ∧ (p → q)) → ¬p | Modus Tollens |
| ((p → q) ∧ (q → r)) → (p → r) | Hypothetical Syllogism |
| ((p ∨ q) ∧ ¬p) → q | Disjunctive Syllogism |
| p → (p ∨ q) | Addition |
| (p ∧ q) → p | Simplification |
| ((p) ∧ (q)) → (p ∧ q) | Conjunction |
| ((p ∨ q) ∧ (¬p ∨ r)) → (q ∨ r) | Resolution |

- I learned that conditional statements play an essential role in mathematical reasoning, in which it has the variety of terminology used to express p → q:
  - “if p, then q”
  - “if p, q”
  - “p is sufficient for q”
  - “q if p”
  - “q when p
  - “a necessary condition for p is q”
  - “q unless ¬p”
  - “p implies q”
  - “p only if q”
  - “a sufficient condition for q is p”
  - “q whenever p”
  - “q is necessary for p”
  - “q follows from p”
- I learned that before proving a valid argument, I should list down all the premises in logical expression.
- By the use of Rules of Inference and other laws, we will come up to a conclusion that "Superman Does Not Exist" logically.

*"If Superman were able and willing to prevent evil, he would do so. If Superman were unable to prevent evil, he would be impotent; if he were unwilling to prevent evil, he would be malevolent. Superman does not prevent evil. If Superman exists, he is neither impotent nor malevolent. Therefor, Superman does not exist."*
  - able (a)
  - willing (w)
  - prevent evil (p)
  - impotent (i)
  - malevolent (m)
  - exist (e)

|| Premises: |
|:--:| :-------: |
|P1| (a ∧ w) → p|
|P2| ¬a → i|
|P3| ¬w → m|
|P4| ¬p|
|P5| e → (¬i ∧ ¬m)|
|∴| ¬e|

SOLUTION:

| Step | Logical Expression | Laws Used | Step | Logical Expression | Laws Used |
|:----:|:----:|:----:|:----:|:----:|:----:|
|1|¬(a ∧ w) ∨ p| A→B ≡ ¬A∨B (P1)|9| w ∨ m | Negation (8)|
|2|p ∨ ¬(a ∧ w)| Commutative (1)|10| ¬w ∨ i | Commutative (7) |
|3|¬(a ∧ w)| Disjunctive Syllogism (2,P4)|11| m ∨ i | Resolution (9,10) |
|4|¬a ∨ ¬w| de Morgan's (3)|12| ¬(¬i ∧ ¬m) → ¬e | Contrapositive (P5) |
|5|¬¬a ∨ i| A→B ≡ ¬A∨B (P2)|13| (i ∨ m) → ¬e| de Morgan's (12) |
|6|a ∨ i| Negation (5)|14| (i ∨ m) | Commutative (11) | 
|7|i ∨ ¬w| Resolution (6,4)|15| ¬e | Modus Ponens (13,14)|
|8|¬¬w ∨ m| A→B ≡ ¬A∨B (P3)|16| ∴ ¬e | |

## Week 4:
- I learned that in Direct Proof, we **assume that P is true** and **show that Q is true**.
- I also learned that in Indirect Proof, we **take ¬Q as a hypothesis** and will **show that ¬P must follow**.
- In Proof by Contraposition or Indirect Proof, if we are given a statement "P implies Q", we will come up with the definition of its Contrapositive "¬Q → ¬P".
- In Vacuous and Trivial Proofs, the technique for that is to know the truth table for Implication where it will always be true.
- In Vacuous Proof, if P is False, then the Implication is True.
- In Trivial Proof, if Q is true, then the Implication is True.
- Some arguments where Q is simple, it's okay to use Contraposition Proof than Direct Proof.
- Contradiction Proof is where we contradicts the first premise that is negated (¬ PREMISE ≡ T).

## Week 5:
- We discussed the Proof of Equivalence or Biconditionals, where it is the combination of the previous proof.
- Proof of Equivalence shows that (p ↔ q) ↔ [(p → q) ∧ (q → p)].
- We discussed the Mathematical Induction wherein the Basic Step is to let P(n) be true, and the Inductive Step is to prove that what is shown is supposed to be true by making the P(n) be P(k) and P(k+1).
- Recursive Induction was discussed where the basic step is to specify the value of the function at zero, and the recursive step that gives a rule for finding its value at an integer from its values at smaller integers.

## Week 6:
- We've discussed the Set Theory.
- I learned that when we are given a two sets with different elements, it is also the same set as long as they were just repeated.
- We've recall the terms that was already discussed in Algebra: Union, Intersection, Set Difference, and Symmetric Difference.
  - UNION: A ∪ B -- {x|(x∈A) ∨ (x∈B)}
  - INTERSECTION: A ∩ B -- {x|(x∈A) ∧ (x∈B)}
  - SET DIFFERENCE: A - B or A \ B -- {x|(x∈A) ∧ (x∈B)}
  - SYMMETRIC DIFFERENCE: A ∆ B -- {x|((x∈A) ∧ (x∉B)) ∨ ((x∈B) ∧ (x∉A))}
- We've discussed that Cardinality is knowing the number of elements in a set.
- Cardinality is denoted by writing |S|, where S is a set.
- If we are asked what is the Cardinality of a given infinite numbers such as natural numbers, it can be defined as "aleph-zero", "alephnought", or "alephnull".

## Week 7:
- I learned that Algorithm is one of the hardest topic in DISMATH.
- An Algorithm is a finite set of precise instructions for performing a computation or for solving a problem.
- I learned that Pseudocode is the high-level description of an algorithm that uses the structural conventions (Input, Body, and Output)
- I learned that **Precondition** describes the valid input whilst **Postcondition** is the output that was satisfied when the program run.
- I learned that in order for the Pseudocode to be correct, the following properties should be obtain:
  - Input
  - Output
  - Defineteness - it is defined precisely
  - Correctness - the output value are correct
  - Finiteness - it is limited with the given input
  - Generality

## Week 8:
- I learned the two types/exampls of Search Algorithm: Linear Search and Binary Search.
- I learned two new terms and symbols that will be used for Pseudocode: floor and ceiling.
- I somehow forgot that when doing Pseudocode, it should be in general not the specific value of the given input.
- I learned the two types/examples of Sorting Algorithm: Bubble Sort and Insertion Sort.
- I learned an example for Greedy Algorithm, the Greedy-Change.
- The growth of functions was introduced and Big-O notation was discussed first.
- In the Growth of Function, it has a constants of C and k that describes as the witnesses.
- Big-O notation is the upper bound of a function.

## Week 9:
- Big-O notation was further explained, and the two remaining Growth of Functions were also discussed.
- Aside for Big-O notation, Big-Omega and Big-Theta are also part of Growth of Functions.
- Big-Omega is the lower bound of a function, while Big-Theta is the upper and lower bound of a function.
- Mathematical definition:
  - Big-O: |f(x)| ≤ |C(g(x))|
  - Big-Omega: |f(x)| ≥ |C(g(x))|
  - Big-Theta: |C1(g(x))| ≤ |f(x)| ≤ |C2(g(x))|
- The Time Complexity of Algorithm was discussed but I'm having a difficulty to determine the comparisons of an algorithm.

## Week 10:  
- I learned the technique on knowing the comparisons of the algorithms that was discussed.  
- We had our 2nd Quiz.  

## Week 11:  
- New topic was discussed, it is said that this topic is the easiest one but its kind of tricky for me.  
- We discussed Graph Theory; in which a graph G = (V,E) consists of V a nonempty set of vertices (or nodes) and E is a set of edges where each of it has either one or two vertices associated with it, called its endpoints.  
- I learned the Handshaking Theorem with a given formula: **2e=∑deg(v)**  
- Königsberg Problem was introduced to us as an introduction for Euler Circuit and Path.  
- Definition:  
  - **Euler Circuit** - It has an Euler Circuit iff a graph has even degree for all nodes/vertices  
  - **Euler Path** - It has an Euler Path if the graph has exactly two (2) nodes/vertices with odd degree.  
- Hamilton Circuit and Path was also discussed; It is also same with Euler Circuit and Paths but the only difference is in Hamilton, instead of passing all through the edges, it should pass all through the vertices/nodes.  
- It is called a Hamiltonian if it is both Circuit and a Path, same goes to Eulerian.  
- I learned how to make a graph out of matrices.  
- The **Isomorphism of Graphs** is when two graphs are still the same when the orientation changes.  
- **Planar Graphs** is done by making the edges not cross each other.  
- There is an **Euler's Formula** for computing the number of regions: **r = e - v + 2**  
- **Kuratowski's Theorem** is when a graph is nonplanar iff it contains a subgraph homeomorphic to the following graph.  
- It is called **Complete Graphs* on *n* vertices, denoted  by Kn, a simple graph that contains exactly one edge between each pair of distinct vertices.  
- Petersen Graph is K3,3.  

