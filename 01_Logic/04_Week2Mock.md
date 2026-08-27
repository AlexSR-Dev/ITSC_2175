04 - Week 2 Part 1 Mock Test:

Part 1 - Logical Equivalence:

1. Explain the meaning of: p = q
- Logical equivalence means that two compound propositions always have the same truth value for every possible 
combination of their propositional variables.

2. "p ∧ q ≡ q ∧ p means that p ∧ q and q ∧ p are literally the same expression."
Is the student correct?
- Its communtative law, in which only the position of propositions are changed, but aren't the same express.
And are instead logically equivalent.




Part II — Tautology, Contradiction & Contingency
3. Classification — 9 points

Classify each expression as a:
Tautology
Contradiction
Contingency

Do not construct a truth table unless you need one.

A. p ∨ ¬p
- Tautology, the final compound-proposition column is true in every row.

B. p ∧ ¬p
- Contradication, the resulting column for the compound is only false.

C. p ∧ q
- Contingency, A contingency is a proposition that is true for some truth-value assignments and false for others.

D. ¬(p ∨ ¬p)
- Contradication, the resulting column for the compound is only false.

E. p ∨ q
- Contingency, because the expression is true for some assignments and false for another.

F. (p ∧ q) ∨ ¬p
- Contingency, the resulting compound column is made up for mixed truth values.

For each, give a one-sentence justification.



4. Truth-Table Classification — 8 points
Construct a truth table for: (p → q) ∨ p

p   |   q   |   (p → q) ∨ p
T       T           T
T       F           T
F       T           T
F       F           T

- Tautology, as the compound's truth value column is only true.





Part III — Laws of Logical Equivalence
5. Identify the Law — 10 points

Identify the law used in each equivalence.

A. p ∧ p ≡ p
- Idempotent Law: Repeating the same proposition with the same operator does not change the result.

B. p ∨ q ≡ q ∨ p
- Commutative Law: Exchange the positions of two propositions. Change the order; preserve equivalence.

C. (p ∧ q) ∧ r ≡ p ∧ (q ∧ r)
- Associative Law: Change the grouping of the outer propositions to the closest proposition in the parentheses.

D. p ∧ (q ∨ r) ≡ (p ∧ q) ∨ (p ∧ r)
- Distributive Law: A proposition outside parentheses is combined with each proposition inside the parentheses according to the distributive pattern.

E. p ∨ (p ∧ q) ≡ p
- Absorption Law: When a outer proposition is confronted with opposite operators and a similar proposition next to it, then the resulting proposition is itself.

F. ¬(p ∧ q) ≡ ¬p ∨ ¬q
- De Morgan's Law: Distribute the negation to the proposition and flip the operator.

G. p ∧ T ≡ p
- Identify Law: The identity element leaves the proposition unchanged.

H. p ∨ T ≡ T
- Domination Law: The constant/truth value takes over.

I. p ∧ ¬p ≡ F
- Complement Law: A proposition combined with its negation produces a constant: F with AND and T with OR.

J. ¬¬p ≡ p
- Double Negation: When a proposition has two negation, then they cancel out.


6. Apply the Law — 10 points
Simplify each expression using an appropriate law.

A. p ∧ p
- Idempotent Law: p

B. q ∨ F
- Identity Law: q

C. r ∧ T
- Identity Law: r

D. p ∨ (p ∧ q)
- Absorption Law: p

E. ¬¬r
- Double Negation: r
For each, name the law you used.






Part IV — Mixed Laws
7. De Morgan's Law — 8 points

Use De Morgan's Law to rewrite:

A. ¬(p ∧ q)
- De Morgan's Law, distributes the negation to the compound and operator:
(¬p V ¬q)


B. ¬(p ∨ q)
- Negation enters the parentheses → every proposition is negated → AND and OR switch places.
(¬p ∧ ¬q)



8. Distributive Law — 6 points
Rewrite: p ∨ (q ∧ r)
using the distributive law.
- Distributive law shares a proposition to the grouped compound:
(p V q) ∧ (p V r)


Then rewrite: p ∧ (q ∨ r)
using the other form.
- Distributive law, The outside proposition is distributed to each proposition inside the parentheses.
(p ∧ q) V (p ∧ r)
Explain what changed structurally.


9. Absorption — 6 points
Simplify:
A. p ∨ (p ∧ q)
- Absorption Law, absorbs the the compound into a single proposition as no matter the result, it will be p's truth value.
p ∨ (p ∧ q) = p

B. p ∧ (p ∨ q)
- Absorption Law, this also gets absorbed. The more complicated expression is logically equivalent to p; therefore, for every possible truth value of p and q, both expressions have the same truth value.value.
p ∧ (p ∨ q) = p

Then explain why the more complicated expression can be reduced to p.





Part V — Conditional & Biconditional Identities
10. Conditional Identity — 6 points

Rewrite: p → q

using the conditional identity.
Then explain why this identity is useful when proving logical equivalence using laws.
The course material specifically describes this identity as a way of converting conditionals into expressions involving AND, OR, and NOT.

p → q = ¬p V q
- The conditional identity is useful because it converts p → q into ¬p ∨ q, allowing us to manipulate the conditional using the other laws of logical equivalence.


11. Biconditional Identity — 6 points

Rewrite: p ↔ q

using the biconditional identity.
Then explain what logical relationship the resulting expression represents.
p ↔ q = (p → q) ∧ (q → p)
- A biconditional requires the conditional relationship to hold in both directions.




Part VI — Proving Equivalence
12. Complete the Proof — 10 points

Prove: ¬p ∨ q ≡ p → q

using a truth table.
You must show the intermediate column(s), not merely state that both expressions have the same truth values.
The course material specifically uses this equivalence as its truth-table example.

p   |   q   |   ¬p  |   ¬p ∨ q  |   p → q
T       T       F           T       T
T       F       F           F       F
F       T       T           T       T
F       F       T           T       T

- The resulting truth value columns for each of the compounds are exactly the same for every row.


13. Law-Based Simplification — 5 points

Simplify the following expression as far as possible: p ∨ (p ∧ q)

Show each step and write the law used beside each step.
For example:
Expression
   ↓ [Law]
Expression
   ↓ [Law]
Final result

- Absorption Law
p ∨ (p ∧ q) ≡ p





Part VII — Integrated Challenge
14. Multi-Law Simplification — 6 points

Simplify: ¬(p ∨ F)

Use logical equivalence laws rather than a truth table.
Show every step and identify the law used.

- Identity Law
¬p



15. Final Challenge — 10 points

Simplify the following as far as possible: ¬(p ∧ T) ∨ (p ∧ ¬p)

You must:
Identify an appropriate law for each transformation.
Show each intermediate expression.
Give the final simplified expression.
State whether the final expression is a tautology, contradiction, or contingency.
Explain why.

- De Morgan's Law
(¬p V ¬T) V (p ∧ ¬p)

- Complement Law
(¬p V ¬T) V F

- Complement Law
(¬p V F) V F

- Identity Law
¬p V F

- Identity Law
¬p