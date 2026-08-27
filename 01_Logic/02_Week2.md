02 - Tautology, Contradtiction & Contingency

Three Types of Compound Propositions:
• Tautology: ALWAYS true (every row T)
• Contraditcion: ALWAYS false (every row F)
• Contingency: Sometimes true, sometimes false.


Classic Tautology: p ∨ ¬p
- Either p is true, or p is not true. No third option.
• "Either it is raining, or it is not raining."
• Always true, regardless of p.


Classic Contradiction: p ∧ ¬p
- p AND not-p. Asking for both at once is impossible.
• "It is raining AND it is not raining."
• Always false, regardless of p.


EX: Classify (p → q) ∨ p
- Build a truth table to idenfity which compound proposition it qualifies for based on its column.
| Proposition | Proposition |   Compound  |    Compound    |
| ----------- | ----------- | ----------- | -------------- |
|      p      |      q      |    p → q    |   (p → q) ∨ p  |
| ----------- | ----------- | ----------- | -------------- |
            Truth Values:
|      T      |      T      |      T      |        T       |
|      T      |      F      |      F      |        T       |
|      F      |      T      |      T      |        T       |
|      F      |      F      |      T      |        T       |

- Final Column is ALL TRUE, the compound proposition is a TAUTOLOGY.








Laws of Logical Equivalence:
- Two compound propositions are logically equivalent if they ALWAYS have the same truth value.
p = q (reads "p is equivalent to q")
• "The glass is half empty" = "The glass is half full"
• !(x > 5) = (x <= 5)

EX: Prove that ¬p ∨ q = p → q
| Proposition | Proposition | Proposition |   Compound  |    Compound    |
| ----------- | ----------- | ----------- | ----------- | -------------- |
|      p      |      q      |     ¬p      |   ¬p ∨ q    |     p → q      |
| ----------- | ----------- | ----------- | ----------- | -------------- |
            Truth Values:
|      T      |      T      |      F      |      T      |        T       |
|      T      |      F      |      F      |      F      |        F       |
|      F      |      T      |      T      |      T      |        T       |
|      F      |      F      |      T      |      T      |        T       |

- Last two columns match in every row -> ¬p ∨ q = p → q are equivalent.



Why We Need Laws
• Truth tables get HUGE with multiple variables.
• Laws allow manipulation of expressions algebraically.
• Rewrite the expression step by step.
• Works no matter how many variables there are.

Laws: Same Operator Inside & Out:
LAW             AND FORM                    OR FORM
Idempotent      p ∧ p = p                   p ∨ p = p
Commutative     p ∧ q = q ∧ p               p ∨ q = q ∨ p
Associative     (p ∧ q) ∧ r = p ∧ (q ∧ r)   (p ∨ q) ∨ r = p ∨ (q ∨ r)


Laws: Mixed Operators:
LAW             Form 1                              Form 2
Distributive    p ∧ (q ∨ r) = (p ∧ q) ∨ (p ∧ r)     p ∨ (q ∧ r) = (p ∨ q) ∧ (p ∨ r)
Absorption      p ∨ (p ∧ q) = p                     p ∧ (p ∨ q) = p
De Morgan's     ¬(p ∧ q) = ¬p ∨ ¬q                  ¬(p ∨ q) = ¬p ∧ ¬q


Laws: Single Proposition Identities:
LAW               AND form              OR form
Identity          p ∧ T = p             p ∨ F = p
Domination        p ∧ F = F             p ∨ T = T
Complement        p ∧ ¬p = F            p ∨ ¬p = T      ¬T ≡ F, ¬F ≡ T
Double Negation   ¬(¬p) = p             (no second form)

- Identity = No change.
- Domination = The constant takes over
- Complement = A thing AND-ed with its negation cancels out.



Conditional & Biconditional Identities:
- These are the BIGGEST workhorses in proofs. MEMORIZE
Conditional Identity:
p → q = ¬p ∨ q

Biconditional Identity:
p ↔ q = (p → q) ∧ (q → p)

- These turn conditional and biconditionals into AND/OR/NOT, which the other laws know how to handle.








Proving Equivalence with Laws:
Rule of Thumb:
Apply these in order whenever you are stuck on a proof:
1. Remove ↔ using biconditional identity: p ↔ q = (p → q) ∧ (q → p)
2. Remove → using conditional identify: p → q = ¬p ∨ q
3. Apply De Morgan's to push ¬ inside parentheses.
4. Apply other laws (associative, commutative, identity, etc).


EX 1: Prove p ∨ (p → q) is a Tautology:
Goal: Simplify the expression until it equals T (true).
1. Remove the → using conditional identity
p ∨ (¬p ∨ q)

2. Regroup using associative law
(p V ¬p) ∨ q

3. Spot p V ¬p (complement law)
= T ∨ q

4. Use domination law to finish
= T

ANS: It is tautology!


EX 2: ¬p → (q → r) = q → (p ∨ r)
Goal: Two conditionas, two negations. Strip them down using identities.
1. Remove both conditionals using conditional identity:
¬¬p V (¬q V r)

2. Simplify the double negation:
p V (¬q V r)

3. Regroup using associative + commutative:
(p V ¬q) V r  - Associative Law
(¬q V p) V r  - Commutative Law

4. Rebuild a conditional using conditional identity in reverse:
¬q V (p V r)  - Associative Law
q → (p V r)   - Conditional Identity

ANS: Both Sides Equal -> Equivalence Proved.



Truth Table or Laws: Which to use?
Truth Tables when:
• Few variables (2 or 3)
• Need to verify, not transfrom
• Find truth value pattern
• Structure is simple.


Use Laws when:
• Many Variables
• Simplify expressions
• Clean algebraic chain
• Structure is complex


Laws - Show the algebraic chain.
Truth Table - Show with a truth table.







ENGLISH EX: Tautologies, contradictions, and logical equivalence:
1. It is not true that the suitcase weight more than 50 pounds and is at least 62 linear inches.
p: The suitcase weighs more than 50 pounds.
q: The suitcase is at least 62 linear inches.
- Its english equivalent to ¬(p ∧ q), by De Morgan's law is equivalent to (¬p ∧ ¬q).
ANS: The suitcase weights at least 50 pounds OR is less than 62 linear inches.


2. It is not true that the pizza has more than 3 types of cheese and at least 4 toppings.
p: The pizza has more than 3 types of cheese.
s: The pizza has at least 4 toppings.
ANS: The pizza has at most 3 types of cheese OR less than 4 toppings.


3. It is not true that the store carries less than 10 types of chips or at most 5 types of dips.
p: The store carries less than 10 types of chips.
q: The store carries at most 5 types of dips.
ANS: The store carries at least 10 types of chips AND more than 5 types of dips.



1. Using the Laws of Propositional Logic to Show Logical Equivalence:
¬(p → q) = p ∧ ¬q

a. Conditional Identity:
¬(¬p V q) = p ∧ ¬q

b. De Morgan's Law:
¬¬p ∧ ¬q = p ∧ ¬q

c. Double Negation:
p ∧ ¬q = p ∧ ¬q



3. Proof: A Logical Equivalence:
a ∧ (a → b) = a ∧ b

1) Conditional Identity:
a ∧ (¬a V b)

2) Distributive Law:
(a ∧ ¬a) V (a V b)

3) Complement:
F V (a V b)

4) Commutative Law:
(a V b) V F

5) Identity Law:
(a V b) = (a V b)



4. Proof: A Logical Statement That is a Contradiction:
¬(a → b) ∧ b

a. Conditional Identity:
¬(¬a V b) ∧ b

b. De Morgan's Law:
(¬¬a V ¬b) ∧ b

c. Associative Law:
¬¬a V (¬b ∧ b)

d. Commutative Law:
¬¬a V (b ∧ ¬b)

e. Complement Law:
¬¬a V F

d. Domination Law:
F



5. Additional Laws of Propositional Logic:
¬(¬(¬p V q) V (p → q))

a. Conditional Identity:
¬(¬(¬p V q) V (¬p V q))

b. Commutative Law:
¬((¬p V q) V ¬(¬p V q))

c. Complement Law:
¬T

d. Complement Law:
F


