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
* t                 5. q → r            Hypothesis
                    6. t                Modus Ponens, applied to lines 4 and 5

NOTE: By lines I mean the 1., 2., etc... NOT the propositions of the argument.


Enlgish Expresssion:
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