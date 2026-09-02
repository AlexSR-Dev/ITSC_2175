06 - Week 3 Zybooks

1.10 Logical Reasoning:

Argument - A sequence of propositions, called hypotheses, followed by a final proposition, called the conclusion.
An arguement is valid if the conclusion is true for every truth assignment to the variables that causes all of the hypotheses to be true,
otherwise the agrument is invalid.

EX:
p → q
p
------
* q

- p and p → q are the hypotheses. q is the conclusion.



1.10.1: The components of a logical argument:
¬q
p → q
------
* ¬p

1) The conclusion is:
¬p, The conclusion is the last proposition in an argument.

2) The proposition ¬q is:
A hypothesis, All propositions except the last proposition are hypotheses.

3) The argument is valid if which proposition is a tautology:
((p → q) ∧ ¬q) → ¬p
- The conjunction of the hypotheses implies the conclusion.



Truth Tables:
- To use a truth table to establish the validity of an argument, all the hypotheses and conclusion must be included.
If the conclusion is true in each of the true hypothese rows, then the argument is valid. However, if the conclusion is false when the hypotheses are true, then the argument is invalid.


1.10.3: Validity of an argument from truth tables:
p → q
p V q
-----
* q

Truth table:
p | q | p → q | p V q |
T | T | T     | T     |
T | F | F     | T     |
F | T | T     | T     |
F | F | T     | F     |

1) In which rows are both hypotheses true?
- Rows 1 and 3.

2) Is the conclusion true in all of the rows where both the hypotheses are true
Yes, The conclusion q is true in rows 1 and 3. The value for q does not matter for all other rows.

3) Is the argument valid?
Yes, as the CONCLUSION is true whenever all of the hypotheses are true.



p
¬p
--
*q

p | q | ¬p
T | T | F
T | F | F
F | T | T
F | F | T

1) In which rows are both the hypotheses true?
- None of the rows, as each rows is either one false.

2) Is the argument valid?
- Yes, since none of the truth assignments causes all of the hypotheses to be true, the argument is valid.


NOTE:
- If none of the truth assignements causes the hypotheses mentioned to become true, then by default the arguement is valid.
- HOWEVER, if a truth assignments causes two of the hypotheses to be true and one has a false conclusion then the entire agrument cannot be VALID.



English Translation:
It is raining today.
If it is raining today, I will not ride my bike to school.
----------------------------------------------------------
* I will not ride my bike to school.

Form - Of an argument expressed in English is acheived by replacing each individual proposition with a variable.
Defining propositional variables p and q to be:
p: It is raining today.
q: I will not ride my bike to school.

Argument's Form:
p
p → q
-----
*q


EX:
p: Akira studied for the test.
q: Akira passed the test.

Akira studied for the test or Akira passed the test.
Akira did not pass the test.
-----------------------------
* Akira studied for the test.

p → q
¬q
------
*p



- When arguments are expressed in English, they may sometimes have known truth values.

1.10.7: Valid and invalid arguments in English.
- The following provided are arguments proven to be valid or not.
(Valid) Argument form A:
¬q
p → q
-----
* ¬p

(Invalid) Argument form B:
¬p
p → q
-----
* ¬q

1)
6 is not a prime number.
If 6 is a prime number, then 4 is a prime number.
-------------------------------------------------
* 4 is not a prime number.
- Invalid, The not proposition is supposed to be 4 not 6.

2)
PI is not a rational number.
If PI is a rational number, then 2PI is a rational number.
----------------------------------------------------------
* 2PI is not a rational number.
- Same, issue also INVALID.



------------------------------------------------------------------------------------------------------
------------------------------------------------------------------------------------------------------


1.11 Rules of Inference with Propositions

Using truth tables to establish the validity of an argument can become tedious, especially if an arguement uses many variables.
The following rules can be used to show that other arguments are valid. The laws of propositional logic can used to establish the
validity of an argument.


Rules of Inference          |       Name
----------------------------------------------------
p                           | 
p → q                       |       Modus Ponens
------                      |
* q                         |
----------------------------------------------------
¬q                          |
p → q                       |       Modus Tollens
------                      |
* ¬p                        |
----------------------------------------------------
p                           |
-------                     |       Addition
* p V q                     |
----------------------------------------------------
p ∧ q                       |
------                      |       Simplification
* p                         |
----------------------------------------------------
p                           |
q                           |       Conjunction
-------                     |
* p ∧ q                     |
----------------------------------------------------
p → q                       |
q → r                       |   Hypothetical Syllogism
-------                     |
* p → r                     |
----------------------------------------------------
p V q                       |
¬p                          |   Disjunction Syllogism
-----                       |
* q                         |
----------------------------------------------------
p V q                       |
¬p V r                      |       Resolution
-------                     |
* q V r                     |



- Validity of an argument can be established by applying the rules of inference and laws of propositional logic in a 'logical proof'.
Logical Proof - Of an argument is a sequence of steps, each consisting of a proposition and a justification.

EX:
(p V r) → q         1. r                Hypothesis
q → t               2. p V r            Addition, applied to line 1
r                   3. (p V r) → q      Hypthesis
-----------         4. q                Modus ponens, applied to lines 2, 3
* t                 5. q → t            Hypothesis
                    6. t                Modus Ponens, applied to lines 4 and 5

NOTE: By lines I mean the 1., 2., etc... NOT the propositions of the argument.


English Expresssion:
If it is raining or windy or both, the game will be cancelled.
The game will not be cancelled.
--------------------------------------------------------------
It is not windy.


- First step to proving the validity of the argument is assign variable names to each of the individual propositions:
w: It is windy.
r: It is raining.
c: The game will be cancelled.

Replace the English phrases with variable names:

(r V w) → c
¬c
------------
* ¬w

- The final step to prove the agrument is valid using a logical proof:
1. (r V w) → c          Hypothesis
2. ¬c                   Hypothesis
3. ¬(r V w)             Modus tollens, 1, 2
4. ¬r ∧ ¬w              De Morgan's Law, 3
5. ¬w ∧ ¬r              Commutative Law, 4
6. ¬w                   Simplification, 5



1.11.2: Appyling the Laws of Inference:
Establish the validity of the following argument:
¬(p ∧ ¬q)
p
----------
* q V r

1. ¬(p ∧ ¬q)        Hypothesis
2. ¬p V ¬¬q         De Morgan's Law, 1
3. ¬p V q           Double Negation, 2
4. p                Hypothesis
5. ¬¬p              Double Negation, 4
6. q                Disjunction Syllogism, 3, 5
7. q V r            Addition, 6


1.11.3: Proof A valid argument:
Complete the proof that establishes the validity of the argument.
x -> y
z V x
-z
-------
* y

1. z V x        Hypothesis
2. -z           Hypothesis
3. x            Disjunction Syllogism, 1, 2
4. x -> y       Hypothesis
5. y            Modus Ponens, 3, 4


1.11.4: Proof A valid argument:
Complete the proof that establishes the validity of the argument.
(a V b) -> (c V d)
¬c
¬d
------------------
* ¬a

1. ¬c                   Hypothesis
2. ¬d                   Hypothesis
3. ¬c ∧ ¬d              Conjunction, 1, 2
4. ¬(c V d)             De Morgan's Law, 3
5. (a V b) -> (c V d)   Hypothesis
6. ¬(a V b)             Modus Tollens, 4, 5
7. ¬a ∧ ¬b              De Morgan's Law, 6
8. ¬a                   Simplification, 7



------------------------------------------------------------------------------------------------------
------------------------------------------------------------------------------------------------------


1.12 Rules of Inference with Quantifiers:

- To apply the rules of inference to quantified expression, like ∀x(P(x) V Q(x)), the quantifier must be removed by plugging
in a value from the domain to replace the variable x.

- A value that can be pluhhed in for variable x is called an element of the domain x.
- Elements of the domain can also be introduced within proof with generic names.
Two Types of named elements used in logical proofs.

• Arbitrary - Element of a domain has no special properties other than those shared by all the elements of the domain.
• Particular - Element of the domain may have properties that are not shared by all the elements of the dmain.

EX: The domain is the set of all integers, 3 is a particular element of the domain.
The number 3 is odd, which is not a property that is shared by all integers.



1.12.1: Definitions of Arbitrary and Particular Elements of a Domain:

1) The domain is the set of all integers:
3 is an integer.
Hypothesis

- Particular, any element defined in a hypothesis is a particular element.


2) The domain is the set of all employees at a company:
c is an arbitrary employee of the company. Element defintion.

- Arbitrary.


3) The domain is the set of all integers:
c is a paritcular integer.
Element defintion.

- Particular.

4) The domain is the set of students enrolled for a class:
Larry is enrolled in the class. Hypothesis.

- Particular, as any element defined in a hypothesis is a particular element.






Rules Existential instantiation and universal instantiation:
- Replace a quantified variable with an element of the domain.

Rules of Existential generalization and Universal generalization:
- Replace an element of the domain with a quantified variablle.


Rules of Inference                          |   Name            | EX
--------------------------------------------------------------------------------------------------------------------------
c is an element (arbitrary or particular)   | Universal         | Izar is a student in the class.
∀xP(x)                                      | Instantiation     | Every student in the class completed the assignment.
-----------------------------------------   |                   | Therefore, Izar completed the assignment.
* P(c)                                      |                   |
--------------------------------------------------------------------------------------------------------------------------
                                            |                   |
c is an arbitrary element                   | Universal         | Let c be an arbitrary integer.
P(c)                                        | Generalization    | c <= c^2
-----------------------------------------   |                   | Therefore, every integer is less than or equal to its square.
* ∀xP(x)                                    |                   |
--------------------------------------------------------------------------------------------------------------------------
                                            |                   |
∃xP(x)                                      | Existential       | There is an integer that is equal to its square.
------------------------------------------  | Instantiation     | Therefore, c^2 = c, for some integer c.
* (c is a particular element) ∧ P(c)        |                   |
--------------------------------------------------------------------------------------------------------------------------
                                            |                   |
c is an element (arbitrary or particular)   | Existential       | Sam is a particular student in the class.
P(c)                                        | Generalization    | Sam completed the assignment.
------------------------------------------  |                   | Therefore, there is a student in the class who completed the assignment.
* ∃xP(x)                                    |                   |
--------------------------------------------------------------------------------------------------------------------------




1.12.3: Correct and incorrect use of generalization and instantiation:

1. | c is an element | Hypothesis
2. | P(c)            | Hypothesis
3. | ∀xP(x)          | Universal generalization, 1, 2

- Incorrect, as an element defined in a hypothesis is always a particular element.
Also, universal generalization can only be applied if the element is arbitrary.



1. | c is an element |  Hypothesis
2. | ∀xP(x)          |  Hypothesis
3. | P(c)            |  Universal Instantiation, 1, 2

- Correct, as universal instantiation can be used with a particular or arbitrary element.



1. | c is an element    |   Hypothesis
2. | P(c)               |   Hypothesis
3. | d is an element    |   Hypothesis
4. | Q(d)               |   Hypothesis
5. | P(c) ∧ Q(d)        |   Conjunction, 2, 4
6. | ∃x(P(x) ∧ Q(x))    |   Existential generalization, 1, 3, 5

- Incorrect, to apply existential generalization, the variable must replace the same single element throughout the
entire compound proposition. For instance, x can replace every occurence of c or d. However, here x replaces both c and d, which is incorrect.



1. | ∃xP(x)                                     | Hypothesis
2. | (c is ane element of the domain) ∧ P(c)    | Existential instantiation, 1
3. | c is an element of the domain              | Simplification, 2
4. | ∃xQ(x)                                     | Hypothesis
5. | Q(c)                                       | Existential instantiation, 3, 4

- Incorrect, the order to apply existential instantiation, the variable x must be replaced with a new element that has not been used before in the proof.
The new element must be given a new name at the place in the proof where existential instantiation is applied.



1.12.4: Completing a proof validity with quantified statements:
The proof below establishes the validity of the following argument:

∀x(P(x) ∧ Q(x))
---------------
* ∀xP(x)

1. ∀x(P(x) ∧ Q(x))              Hypothesis
                                - The proposition is given as a hypothesis in the arg to be proven.

2. c is an arbitrary element    Element Definition
                                - An element can be introduced at any point in a proof.

3. P(c) ∧ Q(c)                  Universal Instantiation, 1, 2
                                - This replaces a variable with an element, indicating that the rules used is instantiation.
                                In universal instantiation, the variable can be reaplced by any element introduced earlier in the proof.

4. P(c)                         Simplification, 3
                                - The rule says for propositions p and q, if (p ∧ q) is true, then p is true.

5. ∀xP(x)                       Universal Generalization, 2, 4
                                - This replaces an element with a variable.
                                In universal generalization, an arbitrary element must be used.




1.12.5:
The proof below establishes the validity of the following argument:

∃xP(x)
∀xQ(x)
-----------------
* ∃x(P(x) ∧ Q(x))

1. ∃xP(x)                                   Hypothesis
2. (c is a particular element) ∧ P(c)       Existential Instantiation, 1
                                            - This replaces a variable with an element of the domain, indicating that the rule used is instantiation.
                                            In existential instantiation, a particular element is introduced that replaces the variable.

3. P(c) ∧ (c is a particular element)       Commutative Law, 2
4. ∀xQ(x)                                   Hypothesis
5. c is a particular element                Simplification, 2
6. Q(c)                                     Universal instantiation, 4, 5
                                            - This replaces a variable with an element of the domain, indicating that the rule used is instantiation.
                                            In universal instantiation, an arbitrary or particular element may be used.

7. P(c)                                     Simplification, 3
8. P(c) ∧ Q(c)                              Conjunction, 6, 7
9. ∃x(P(x) ∧ Q(x))                          Existential generalization, 5, 8
                                            - This step replaces an element of the domain with a variable.
                                            In existential generalization, an abitrary or particular element may be used.




1.12.6: Completing a Proof of Validity with Quantified Statements:
The following argument is expressed in English. The domain is the set of students enrolled in a class:

Every student who stayed up too late missed the test.
Juan is enrolled in the class.
Juan did not miss the test.
-----------------------------------------------------
* Some student did not stay up too late.

-The first step in proving that the argument is valid is to determine the form of the argument. Define the folloinw two predicates:
S(x): x stayed up too late.
M(x): x missed the test.

The form of the argument is:
∀x(S(x) -> M(x))
Juan, a student in the class
-M(Juan)
----------------------------
* ∃x-S(x)

- Now complete the proof of the argument:

1. ∀x(S(x) -> M(x))                     Hypothesis
2. Juan, a student in the class         Hypothesis
3. S(Juan) -> M(Juan)                   Universal Instantiation, 1, 2        
                                        - This replaces a variable with an element of the domain, indicating that the rule is instantiation.
                                        Universal instantiation can be used with a particular or arbitrary element of the domain.


4. -M(Juan)                             Hypothesis
5. -S(Juan)                             Modus Tollens, 3, 4
                                        - S(Juan) and M(Juan) are both propositions.
                                        This rules says that the two propositions
                                        S(Juan) -> M(Juan)
                                        -M(Juan), implies -S(Juan).

6. ∃x-S(x)                              Existential Generalization, 2, 5
                                        - This replaces an element of the domain with a variable, indicating that the rule used is generalization.
                                        Existential generalization can be used with a particular or abitrary element of the domain.






1.12.8: Proof A valid argument with quantified statements:
Complete the proof that establishes the validity of the argument below by adding the correct justification:

∃x(P(x) V Q(x))
∀x-P(x)
---------------
* ∃xQ(x)

1. ∃x(P(x) V Q(x))                                  Hypothesis
2. (c is a particular element) ∧  (P(x) V Q(x))     Existential Instantiation, 1
3. c is a particular element                        Simplification, 2
4. (P(x) V Q(x)) ∧ (c is a particular element)      Commutative Law, 2
5. P(x) V Q(x)                                      Simplification, 4
6. ∀x-P(x)                                          Hypothesis
7. -P(c)                                            Universal Instantiation, 3, 6
8. Q(x)                                             Disjunction Syllogism, 5, 7
9. ∃xQ(x)                                           Existential Generalization, 3, 8


1.12.9: Complete the proof that establishes the validity of the argument:
∀x(P(x) -> Q(x))
-∀xQ(x)
----------------
* ∃x-P(x)

1. -∀xQ(x)                                      Hypothesis
2. ∃x-Q(x)                                      De Morgan's Law, 1
3. (c is a particular element) ∧ -Q(c)          Existential Instantiation, 2
4. c is a particular element                    Simplification, 3
5. -Q(c) ∧ (c is a particular element)          Commutative Law, 3
6. -Q(c)                                        Simplification, 5
7) ∀x(P(x) -> Q(x))                             Hypothesis
8) P(c) -> Q(c)                                 Universal Instantiation, 4, 7
9) -P(c) V Q(c)                                 Conditional Identity, 8
10) Q(c) V -P(c)                                Commutative Law, 9
11) -P(c)                                       Disjunctive Syllogism, 6, 10
12) ∃x-P(x)                                     Existential Generalization, 4, 11






1.12.10: Correct and Incorrect use of Generalization and Instantiation:

1. ∃xP(x)                                       Hypothesis
2. (c is a particular element) ∧ P(c)           Existential instantiation, 1
3. ∃xQ(x)                                       Hypothesis
4. (c is a particular element) ∧ Q(c)           Existential Instantiation, 3

- Incorrect, as a new element with a new name must be used for each use of existential instantiation.
An example would be variable name 'd', used in the last line would become correct: (d is a particular element) ∧ Q(d) 




1.12.1: Rules of Inference with Quantifiers

1)
The domain is the set of professionals attending a conference.

Every delegate did not register early.
Every delegate who asked questions either registered early or gave a presentation (or both).
--------------------------------------------------------------------------------------------
* Every delegate who asked questions gave a presentation.


Form of the Argument:
∀x(-Q(x))
∀x(P(x) -> (Q(x) V R(x)))
-------------------------
* ∀x(P(x) -> R(x))

Select the definitions for predicates P, Q, and R.
P(x) : x asked questions.
Q(x) : x registered early.
R(x) : x gave a presentation.




2)
The following argument is invalid

∃x(P(x) ∧ Q(x))
∀x(Q(x) -> P(x))
----------------
* ∀xP(x)

- Suppose that the domain of x is the set {a, b}. Fill the table values that prove that the argument is invalid.
     P  |  Q  |
---------------
a |  T  |  T  |
b |  F  |  F  |

∃x(P(x) ∧ Q(x)) is true because P(a) ∧ Q(a) is true.
∀x(Q(x) -> P(x)) is true because Q(x) -> Q(x) is true for both inputs a and b.
However, since P(b) = F, ∀xP(x) is false.

In-Depth Explanation:
First Hypothesis:
∃x(P(x) ∧ Q(x)), at least a domain is true, in this case would be row 'a' entirely True. To satisify the proposition.

Check a: P(a) ∧ Q(a)
         T ∧ T = T

∃x(P(x) ∧ Q(x)) = T


Second Hypothesis:
∀x(Q(x) -> P(x)), every domain must evaluate as true.

check a: T -> T = T
check b: F -> F = T

- Why F, F, for row b is to prove the counterexample to the conclusion.
Since both are true: ∀x(Q(x) -> P(x)) = T


Combine the Hypotheses with OR: T V T = T, Hypothesis = T.

Now evaluate the conclusion: ∀xP(x)
Check: P(a) = T
HOWEVER, P(b) = F

As the conclusion, uses the universal quantifier it means every element must be true: ∀xP(x) = F



3)
The following argument is invalid:

∃x(P(x) ∧ -Q(x))
∀x(Q(x) -> P(x))
----------------
* ∀x-P(x)

The domain of x is the set of positive integers. Select a definition for each predicate P and Q that proves that the argument is invalid.

P(x): x is a composite.
Q(x): x is a multiple of 4.

For the first hypothesis: ∃x(P(x) ∧ -Q(x))
- It is true there exists a positive integer thats x is composite and is not a multiple of 4. Example is 6.

For the second hypothesis: ∀x(Q(x) -> P(x))
- It is true that for every positive integer, if x is a multiple of 4, then x is composite to true for all in the proposition.

The conclusion: ∀x-P(x)
- Is false as not every integer is not composite, for instance 4.

Thus the hypotheses are true and the conclusion is false, the argument is invalid.