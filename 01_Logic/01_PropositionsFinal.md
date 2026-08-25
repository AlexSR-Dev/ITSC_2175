01 - Propositions Final Exam:

Part 1 - Propositions and Logical Operations

1) Proposition Identification:
For each statement, determine whether it is a proposition or not a proposition.
A) Charlotte is located in North Carolina.
- It is a proposition. It poses an unknown statement that can either be true or false.

B) Please close this window.
- Not a proposition. It poses a command rather than a statement to be assert as true or false.

C) Is Charlotte the largest city in North Carolina?
- Not a proposition. It poses a question, although it can be assert as true or false, it requires more information.

D) All politicans are honest.
- Is a proposition. It poses an opinion that can decided between true or false.

E) 17 is a prime number.
- Is a proposition. It also poses an opinion that can result to either true or false.

F) What an incredible sunset!
- Not a proposition. It poses an announcement, rather than an unknown statement that may be backed logically.

G) The patient may have an undiagnosed illness.
- Is a proposition. It poses an unknown statement that may result in true or false based on logic.

H) x + 4 = 9
- Is a proposition. As this equation can be assessed as true or false based on the relevant information of x.



2. Propositional Variables:
Consider:
- p: The student completed the assignment.

A) What does p represent?
- A proposition that can have a true value of either true or false based on its statement.

B) What is the difference between 'p' and the truth value of p?
- Variable p is an indication of the proposition provided that can therefore result in its truth value which is the
representation of the statement's condition.

C) Suppose you do not currently know whether the student completed the assignment. Does that prevent p from being a 
proposition? Explain.
- No, p will remain a proposition, but will instead have a truth value of being undetermined due to the
limited information to assert it.



3. Translate the Logical Notation:
- p: The patient took the medication.
- q: The patient experienced nausea.
- r: The patient experienced migraines.

A) The patient experienced nausea and migraines.
- 'q ∧ r'
Firstly, the proposition statement mentions nausea (q) with a conjunction (AND) to migraines (r) for this patient.

B) The patient took the medication or experienced migraines.
- 'p ∨ r'
This proposition mentions medication (p) with a disjunction (OR) to migraines (r) to what the patient took.

C) The patient did not experience migraines.
- '¬r'
This proposition only mentions a single variable (r) with its negation (NOT) experience.

D) The patient took the medication but experienced nausea.
- 'p ∧ q'
This proposition mentions two variables that had occur in conjunction to one another.

E) The patient did not take the mediciation or did not experience nausea.
- '¬p ∨ ¬r'
Two variables had been negated in disjunction to each other.



4. Logical Operators:
For each operator below:
1. State its name.
2. State what is requires for the resulting proposition to be true.
3. Give its symbol.

A) Conjunction
- AND
- It requires both propositions to have the truth value of true.
- ∧

B) Disjunction / inclusive OR
- OR
- It requires one or both of the propositions to have a truth value of true.
- ∨

C) Exclusive OR
- XOR
- It requires only one of the propositions to have a truth value of true.
- ⊕

D) Negation
- NOT
- It requires the proposition to initial have a true value of false to inverse its truth.
- ¬



5. Inclusive vs. Exclusive OR
Consider the statement: "You may have coffee or tea with breakfast."

Inclusive OR - Basically the same truth values that a regular disjunction has in which one or both of the propositions
need to be true for the overall truth value to become true.
Coffee      |       Tea         |       Disjunction
Yes         |       No          |           T
No          |       Yes         |           T
Yes         |       Yes         |           T
No          |       No          |           F

Exclusive OR - A single difference to a normal disjunction, in which only one of the propositions need to be true.
However, if both are true, then the overall truth value becomes false.
Coffee      |       Tea         |       Disjunction
Yes         |       No          |           T
No          |       Yes         |           T
Yes         |       Yes         |           F
No          |       No          |           F





Part 2 - Compound Propositions:
6. Truth-Value Evaluation
Suppose:
- p = T
- q = F
- r = T

Determine the truth value of each:
A) p ∧ q
- False
The conjunction has a true and false value, in which neither are both true, therefore by default results to false.

B) p ∨ q
- True
The disjunction has one true value, in that by default the compound proposition becomes true.

C) q ∨ r
- True
The disjunction still has one true value.

D) ¬p
- False
The negation of the proposition 'p' becomes the inverse of its original truth value true into false.

E) ¬q
- True
The inverse of 'q' occurs by negation, resulting in a truth value of true.

F) p ∧ (q ∨ r)
- True
The compound proposition in parentheses is evaluated first in which the disjunction of (F OR T) results in T.
Lastly the conjunction of p and truth value of the parentheses results to True, (T AND T).

G) (p ∧ q) ∨ r
- True
The parentheses is evaluated first, resulting in false by conjunction (T AND F). Lastly the disjunction between
the parentheses and r is evaulated resulting T, (F OR T).

H) ¬(p ∨ q)
- False
The parentheses is evaluted, resulting in true by disjunction (T OR F). Lastly the negation is evaulated on the result
of the parentheses, resulting in the reseverse truth false from true into FALSE.



7. Order of Operations:
Consider: ¬p ∨ q ∧ r

Assume:
- p = T
- q = F
- r = T

A) Which operation should be evaluated first?
- Negation has higher precedence in the logical order of operations. Resulting in false.

B) Which should be evaluated next?
- The conjunction as it is the second highest in priority by order of operation. Resulting in (F AND T) false.

C) Determine the final truth value.
- The final truth value is evaluted at the disjunction with (F OR F), resulting in FALSE.

D) Explain why simply evaluating the expression strictly from left to right would be inappropriate.
- Not only would it violate the order of operations, but the resulting truth value would become true instead.



8. Truth Tables:
Construct the complete truth table for: p ∨ ¬q
- First account for the variables for how many rows will be made: 2^2 = 4.
- Also follow the pattern from the rightmost except the negation with the pattern TFTF, and double it for each column
beside it to the left.
| Proposition | Proposition | Proposition | Compound   |
| ----------- | ----------- | ----------- | ---------- |
|      p      |      q      |     ¬q      |    p ∨ ¬q  |
| ----------- | ----------- | ----------- | ---------- |
            Truth Values:
|      T      |      T      |      F      |      T     |
|      T      |      F      |      T      |      T     |
|      F      |      T      |      F      |      F     |
|      F      |      F      |      T      |      T     |


Then construct the complete truth table for: (p ∧ q) ∨ ¬p
| Proposition | Proposition | Proposition |    Compound   |
| ----------- | ----------- | ----------- | ------------- |
|      p      |      q      |     ¬p      | (p ∧ q) ∨ ¬p  |
| ----------- | ----------- | ----------- | ------------- |
            Truth Values:
|      T      |      T      |      F      |       T       |
|      T      |      F      |      F      |       T       |
|      F      |      T      |      T      |       T       |
|      F      |      F      |      T      |       T       |



9. Number of Rows:
Without constructing the tables, determine how many rows would be required for a truth table containing:

A) 2 propositional variables
- 4, since there the variables represents two truth values and there are n variables, thus 2^2 = 4.
Therefore the rightmost will have pattern TFTF, its neighbor to its left TTFF.

B) 3 propositional variables
- 8, as there is 3 variables, thus 2^3 = 8. lastly the rightmost will have the pattern TFTF, its neighbor to its
left TTFF and to its left TTTTFFFF.

C) 4 propositional variables
- 16, as there is 4 variables, 2^4 = 16. Bascially from the rightmost variable it has the pattern TF and it doubles
for every neighbor to its left.

D) 5 propositional variables
- 32, as there is 5 variables, 2^5 = 32. Same pattern starting from TF and doubles for every variable to its left.



10. Evaluate by Decomposition:
Suppose:
- p = F
- q = T
- r = F

Evaulate: ¬(p ∨ r) ∧ (q ∨ p)
ANS:
- Firstly we replace the compound proposition with its truth values: ¬(F ∨ F) ∧ (T ∨ F).
Secondly, we evaluate the parentheses therefore from the left its disjunction and also the right: ¬(F) ∧ (T).
Thirdly, we evalulate the negation, resulting in (T) ∧ (T).
Lastly, the conjunction resulting in a truth value of TRUE.




Part 3 - Conditional Statements:
11. Identify the Components:
Consider: If a student studies, then the student passes the exam.
- p: The student studies.
- q: The student passes the exam.

A) What is the symbolic representation?
- The representation of conditional for proposition is '→'.

B) Which proposition is the antecedent?
- The proposition would be (p) the student studies.

C) Which proposition is the consequent?
- Consequent, you mean the conclusion, then it would be variable 'q'.

D) In ordinary language, what does the conditional assert?
- The relationship, If the student studies (p), then the student passes the exam (q).



12. Conditional Truth:
Suppose: p → q

Determine whether the conditional is true or false in each case:
| `p` | `q` | `p → q` |
| --- | --- | ------- |
| T   | T   | T       |
| T   | F   | F       |
| F   | T   | T       |
| F   | F   | T       |

Then explain why the particular false case is false.
- A conditional p → q is false only when p is true and q is false.
Because the conditional makes a claim specifically about what happens when p occurs. If p happens and q does not, the 
conditional's claim has been violated. When p is false, the conditional has not been contradicted.


13. Conditional Language:
- p: You complete your homework.
- q: You receive full credit.

Translate each statement into logical notation.
A) If you complete your homework, then you receive full credit.
- `p → q`

B) You receive full credit if you complete your homework.
- `p → q`
Only the wording is different, same hypothesis that you complete you homework and same conclusion the full credit.

C) Completing your homework is sufficient for receiving full credit.
- `p → q`
Different wording, same conditional references.

D) Receiving full credit is necessary for completing your homework.
- `q → p`



14. Converse, Inverse, Contrapositive:
Given: p → q

A) Write the converse.
- `q → p`

B) Write the inverse.
- `¬p → ¬q`

C) Write the contrapositive.
- `¬q → ¬p`

D) Which of the three is logically equivalent to the original conditional?
- The contrapositive, but testing them with the false case of true and false. As a result only the contrapositive
has the same result as the original condition. Additionally, the condition corrected it self by reversing its
truth values twice into the original.

E) Are the converse and inverse logically equivalent to each other?
- They are logically equivalent to each other, but that equivalence comes from their logical relationship—not because 
both “reverse the truth values.” Converse - Swap the propositions → q → p. Inverse - Negate both propositions → ¬p → ¬q.



15. Apply the Transformations:
- p: A number is divisible by 4.
- q: A number is even.

A) Original conditional
- 'p → q'

B) Converse
- 'q → p'

C) Inverse
- '¬p → ¬q'

D) Contrapositive
- '¬q → ¬p'




Part 4 - Biconditional and Integrated Reasoning:
16. Biconditional:
Let:
- p: A number is divisible by 2.
- q: A number is even.

Consider: p ↔ q
A) What is the name of this logical operation?
- Its a biconditional.

B) Under what condition is a biconditional true?
- When both variables has the same truth values, then its evaluated as true, whether is both trues or both falses.

C) What does the statement mean in ordinary language?
- 'p IF AND ONLY IF q'

D) How does the biconditional differ from p → q?
- A biconditional is better understood as asserting two conditionals simultaneously: p ↔ q means p → q and q → p.
Establishes the relationship in both directions.


17. Evalute a Compound Conditional:
Suppose:
- p = T
- q = F
- r = T

Evaluate: (p ∧ q) → r
- Firstly, evaluate the conjunction in the parentheses, which would become false (T AND F).
Secondly, evaluate the conditional with (If F THEN T), which results in a overall truth value of true, A conditional 
with a false antecedent is true, regardless of the consequent.


18. Integrated Translation:
Let:
- p: The student is a senior.
- q: The student is at least 17 years old.
- r: The student may park in the school parking lot.

Translate:
A person may park in the school parking lot if and only if the person is a senior and at least 17 years of age.
Your answer should use the appropriate logical operators and parentheses.
- r ↔ (p ∧ q)

Then identify:
a) the overall logical structure.
- Firstly, we began with a biconditional expression with 'IF AND ONLY IF' between (r) and the result of a conjunction
between (p) the senior and (q) thier age.

b) the component proposition on the left of the biconditional.
- The ability for the student to park in the school parking lot, represented with variable (r).

c) the compound proposition on the right.
- A conjunction between (p) the student's senior status and (q) the student's age of at least 17. The final result
becoming the final conclusion for the biconditional expression.




Part 5 - Conceptual Reasoning:
19. Diagnose the Student:
A student says:
"The statement 'It might rain tomorrow' isn't a proposition because we don't know whether it's true yet."

Is the student's reasoning correct?
Explain precisely what is wrong or right about the statement.
- The statement itself is a proposition as it is a declarative statement yet to be evaluated as soon as it is
directed to a point in time. Since, it predicates an event from today, the evaluation of the statement is yet
to be revealed, therefore becoming a proposition.


20. Diagnose the Student:
A student says:
"p ∧ q means that at least one of p or q must be true."

Evaluate this explanation.
If it is incorrect, explain what the student is confusing it with.
- The explanation is incorrect, as it evaluates a disjunction (OR) not what is provided which is a conjunction (AND).
Therefore, both p and q must have the truth value of true for the overall result to become true.


21. Diagnose the Student:
A student says:
"The conditional p → q is false whenever p is false because the condition wasn't satisfied."

Evaluate this reasoning.
Do not simply state the correct truth-table entry. Explain the conceptual error.
- They are treating a false antecedent as making the entire conditional false.
But p → q is false only when p is true and q is false.


22. Diagnose the Student:
A student says:
"The converse of p → q is ¬p → ¬q."

Identify what operation the student has actually described and explain the distinction.
- The student describied the converse of the proposition in which it the position of the variables are
switched: 'q → p'. And what the student identified was the inverse of the compound proposition.


Part 6 - Final Challenge:
23. Full Logical Analysis:
Let:
- p: A student completes the required coursework.
- q: A student passes the final exam.
- r: A student passes the course.

Consider:
If the student completes the required coursework and passes the final exam, then the student passes the course.
A. Translate the statement into logical notation.
- (p ∧ q) → r

B. Identify the antecedent.
- The conjunction of (p ∧ q) in which the student completes the required coursework and passes the final exam.

C. Identify the consequent.
- Variable (r), the student passes the course.

D. Suppose p = T, q = F, and r = F. Determine the truth value of the entire conditional.
- (T ∧ F) → F, becomes (F) → F, to finally true.

E. Explain your reasoning step-by-step.
- “The conjunction p ∧ q is false because p is true and q is false. Therefore the antecedent of the conditional is 
false. A conditional is false only when its antecedent is true and its consequent is false. Since the antecedent is 
false, the conditional is true.”

F. Construct the complete truth table for the expression.
| `p` | `q` | `r` | `(p ∧ q) → r` |
| --- | --- | --- | ------------- |
| T   | T   |  T  |       T       |
| T   | T   |  F  |       F       |
| T   | F   |  T  |       T       |
| T   | F   |  F  |       T       |
| F   | T   |  T  |       T       |
| F   | T   |  F  |       T       |
| F   | F   |  T  |       T       |
| F   | F   |  F  |       T       |