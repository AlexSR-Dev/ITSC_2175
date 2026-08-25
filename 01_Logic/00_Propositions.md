Concept 1: Propositions:
- A declarative statement that is either True or False.
Questions, commands, and exclamations are not propositions.


Consider these three statements:
A) The server is running.
- This is a proposition as it poses a logical statement.

B) Is the server running?
- This is not a proposition, but a question.

C) Start the server!
- This is not a proposition as it annouces an action rather than posing a condition.


Classify these:
1. The CPU temperature is 75°C.
- Is a proposition as It is a declarative statement that can be either true or false.

2. Is the CPU temperature 75°C?
- Not a proposition. It asks for information rather than asserting something that can be assigned a truth value.

3. Check the CPU temperature.
- Not a proposition, instead a command to execute.

4. The CPU temperature might be 75°C.
- A proposition is a declarative statement that is either true or false, even if we currently don't know its truth 
value or the statement expresses an opinion.



Last Question: "This algorithm is inefficent."
- The sentence is structured as an  opinion that provides an unknown truth that can be evaluated as true or false. Therefore it must be a proposition.


Checkpoint:
Unknown truth value → can still be a proposition.
Opinion → can still be a proposition.
Question → not a proposition.
Command → not a proposition.
Exclamation → not a proposition.
Declarative statement capable of being true or false → proposition.


1.1.1: Identifying Propositions:
A) Find the product of 32 and 10.
- A command.

B) 5 + 7 = 12.
- Proposition.

C) 11 is an even number.
- Proposition.

D) Suppose two consecutive odd integers exist.
- A commond as "Suppose" assigns the reader with a directive instead of declarative.





Phase 1.5 - Propositional Variables:

p - Is a propositional variable that represents a proposition.
p: January has 31 days.
- p acts as a compact label for the entire proposition.
- The proposition represented by p has a truth value of true or false.

| Symbol | Represents          | Has           |
| ------ | ------------------- | ------------- |
| `p`    | A proposition       | A truth value |
| `q`    | Another proposition | A truth value |
| `r`    | Another proposition | A truth value |

- Thus p "represents a statements" and can have a truth value evaluated: "p = True".


Symbols:
p: The server is online.
q: The databse is connected.

What does the expression "p ∧ q" represent?
- The symbol "∧" represents conjuctions, thus "and".
- Resulting in "The server is online AND the database is connected."
- Thus, the conjunction can only be true, when both propositions are true. Else false.


Truth Table - Displays the truth value of a every logical operation proposition for every possible combination of truth values.

| Proposition | Proposition | Conjuction |
| ----------- | ----------- | ---------- |
|      p      |      q      |    p ∧ q   |
| ----------- | ----------- | ---------- |
            Truth Values:
|      T      |      T      |      T     |
|      T      |      F      |      F     |
|      F      |      T      |      F     |
|      F      |      F      |      F     |


Expressing Conjunction in English:
EX:
p: The sauce looks disgusting.
h: The sauce tastes delicious.

p AND h: "The sauce looks disgusting and tastes delicious."

p BUT h: "The sauce looks disgusting, but tastes delicious."

DESPITE the fact that p, h: "Despite the fact that the sauce looks disgusting, it tastes delicious."

ALTHOUGH p,h: "Although the sauce looks disgusting, it tastes delicious."






The Disjunction Operation:

Denoted as "p ∨ q" and read as "p or q".
- Basically the OR conditional operator.
- Thus, the proposition is true if either one is true. Or false if both propositions are false.

| Proposition | Proposition | Conjuction |
| ----------- | ----------- | ---------- |
|      p      |      q      |    p ∨ q   |
| ----------- | ----------- | ---------- |
            Truth Values:
|      T      |      T      |      T     |
|      T      |      F      |      T     |
|      F      |      T      |      T     |
|      F      |      F      |      F     |

- Since OR in english can have broad meanings, we have "exlusive or" and "inclusive or".

EXCLUSIVE OR - When one proposition is true and other is false, thus can ONLY be evaluated as true.
INCLUSIVE OR - When both propositions are true, thus evaluated as true. Follows normal disjunction.

EX: "Lucy opens the windows or doors when warm."
- This is an inclusive OR as she would possibly choose both or either or. Additionally, this statement doesn't
pose to be decisive on choosing one over the other.


EXERCISES: Evaluate whether each statement is true or false. Use inclusive OR.
A) "4 is an even number of 4 is a prime number?"
- True, since one of the two statements must evaluate to true, thus by disjunction TRUE OR FALSE => TRUE.

B) "5 is a prime number of 3 is a prime number?"
- True, as both statements are evaluated as true by disjunction.

C) "2 is a negative number of -3 is a positive number?"
- False, both statements in the disjuction are false, thus evaluated overall as false.



EXCLUSIVE OR:
- Denoted with the symbol "⊕".
- Almost follows normal disjunction, BUT does not consider double truths as true.
| Proposition | Proposition | Disjunction|
| ----------- | ----------- | ---------- |
|      p      |      q      |    p ⊕ q  |
| ----------- | ----------- | ---------- |
            Truth Values:
|      T      |      T      |      F     |
|      T      |      F      |      T     |
|      F      |      T      |      T     |
|      F      |      F      |      F     |






Negation Operation:
- Operates on ONLY ONE proposition, reverses the truth value of that proposition.
Read as "not p".

| Proposition |   Negation  |
| ----------- | ----------- |
|      p      |     ¬p      |
| ----------- | ----------- |
        Truth Values:
|      T      |      F      |
|      F      |      T      |

EXERCISE: Assume propositions p, q, and r have the following truth values:
- p is true.
- q is true.
- r is false.

What are the truth values for the following compound propositions?
1) p ∧ q
- True, as "True AND True" in conjuction results in truth value of true.

2) ¬r
- True, as "NOT r" results in a reverse truth value of true from false.

3) p ∧ r
- False, as "True AND False" in conjunction results in a truth value of false.

4) p ∨ r
- True, as "True OR False" in disjunction results in a truth value of true overall.

5) p ∨ q
- True, as "True OR True" in disjunction results in true.


Challenge:
1. The propositional values 'p', 'q', 'r', and 'w' we defined as follows.
- p: Felicia was tired.
- q: Felicia went to the game.
- r: Felicia went to a movie.
- w: Felicia had a headache.

Proposition in words: Felicia did not go to the movie.
What is "Proposition in symbols?"
- The proposition in symbols from the english version would be the NOT operator, as the piece of relevant
information provide is the movies, as variable 'r' is the only verified indication to this info.
ANS: ¬r


2. Select the correct truth value for each proposition.
- p: True
- q: False
- r: True
- w: true

Select the correct truth value for each proposition:
A) q ∧ p
- False, the AND operator (conjunction) requires both proposition truth values to be true for the overall 
result to be true, else will become false.

B) w ∨ r
- True, the OR operator (disjunction) only requires one proposition to have a true truth value for the
overall result to become true.

C) ¬q
- True, the NOT operator (negation) reverses the initial truth value, in which case was false into true.


3. Select the correct truth value for each proposition.
A) (5 + 2 = 6) ∧ (5 X 3 = 16)
- False, both propositions are clearly wrong, thus the conjunction (AND) has a truth value of false.

B) (5 - 1 = 6) ∨ (14 + % = 19)
- True, only one proposition was true, resulting in this disjunction (OR) to become true.

C) ¬(6/2 = 3)
- False, initial the true value was true, however the negation (NOT) reversed the truth value into false.






1.2 - Evaluating Compound Propositions:
A compound proposition are individual propositions with logical operations.
- Now these compounds can use more than one operation: "p ∨ ¬q"


Order of Operation without Parentheses:
1. ¬ (NOT)
2. ∧ (AND)
3. ∨ (OR)
- Note parethenese always go first with the exception of NOT, already being applied first with its own.

EX: Evaluating Compound Propositions
p: T,       q:F,        r:T

To evaluate p ∧ ¬(q V r)
- Fill the truth values provided.

1. T ∧ ¬(F V T)
- Evaluate the operation by parentheses first.

2. T ∧ ¬(T)
- Evaluate the NOT operator.

3. T ∧ F => F
- The compound proposition evaluates to false, based on conjuction of T AND F.



EXERCISE: Assume the propositions 'p', 'q', 'r' have the followin truth values:
- p is true.
- q is true.
- r is false.

What are the truth values for the following compound propositions?
1) p ∨ ¬q
- True, based on disjunction (OR) true or false results in a truth value of true.

2) ¬r ∧ (p ∨ ¬q)
- True, (p OR (NOT q)) => (T OR F) => T, then theres (NOT r) => T, lastly T AND T => true based on the last conjunction by order.

3) ¬(p ∧ ¬ r)
- False, firsly operate the parentheses (T AND (NOT F)) => (T AND T) => T, lastly the negation NOT(T) => false truth value.

4) (p ∨ r) ∧ ¬p
- False, firsly operate the parentheses (T OR F) => T, and then the negation for q (NOT T) => F, lastly the
conjunction (AND) for both truth values (T AND F) => F.




English into compound propositions:
- Identify the order of proposition based on the order provided.

EX:
p: The children have tacos.
q: The children go to the butterfly house.
r: The children have cookies.

1) Proposition in words: "It is not true that the children go to the butterfly house and have cookies."
- Firstly, it identifies the NOT around both variables that are conjoined.
- "¬ (q ∧ r)"

2) The children have cookies but not tacos.
- Identify that tacos are under NOT, but theres isn't and option for OR, so AND must be by default.
- "r ∧ ¬p"

3) The children go to the butterfly house and have cookies or tacos.
- Firstly, there is the OR operations then a AND operator.
- "q ∧ (r ∨ p)"



Filling in the rows of a Truth Table:
- Every possible combination of truth assignments for the statement's variables.
If a compound proposition has n variables, there are 2^n rows.

- Starting from the rightmost variable column use alternating T and F pattern.
- The next column to the left alternate TT and FF pattern.
- Next column to the left alternate TTTT and FFFF pattern.
- For each new column the number of T's and F's in the pattern DOUBLES.

EX: (p ∧ r) ∧ ¬q
3 variables -> 2^3 = 8 rows.

| Proposition | Proposition | Proposition |    Compound    |
| ----------- | ----------- | ----------- | -------------- |
|      p      |      q      |      r      |  (p ∧ r) ∧ ¬q  |
| ----------- | ----------- | ----------- | -------------- |
            Truth Values:
|      T      |      T      |      T      |        F       |
|      T      |      T      |      F      |        F       |
|      T      |      F      |      T      |        T       |
|      T      |      F      |      F      |        T       |
|      F      |      T      |      T      |        F       |
|      F      |      T      |      F      |        F       |
|      F      |      F      |      T      |        T       |
|      F      |      F      |      F      |        F       |

NOTE:
When identifying the amount of rows, duplicate variables don't count in the n result for 2^n.



Negation Compound Proposition Truth table:
- Negation obtains two separate columns, its normal variable and its negation. It follows the same pattern vice versa.

| Proposition | Proposition | Proposition | Proposition |    Compound    |     Final Compound
| ----------- | ----------- | ----------- | ----------- | -------------- | --------------------
|      p      |      q      |      r      |      ¬q     |    (p ∧ r)     |       ¬q ∧ (p ∧ r) 
| ----------- | ----------- | ----------- | ----------- | -------------- | --------------------
            Truth Values:
|      T      |      T      |      T      |      F      |        F       |          F
|      T      |      T      |      F      |      F      |        F       |          F
|      T      |      F      |      T      |      T      |        T       |          T
|      T      |      F      |      F      |      T      |        T       |          T
|      F      |      T      |      T      |      F      |        F       |          F
|      F      |      T      |      F      |      F      |        F       |          F
|      F      |      F      |      T      |      T      |        T       |          T
|      F      |      F      |      F      |      T      |        F       |          F

NOTE:
This is every possible truth value combination for this compound final result.





1.3: Conditioanl Statements
- Denoted with the symbol "→".
"p → q" reads "if p, then q".

- The proposition "p → q" is false if p is true and q is false; otherwise, "p → q" is true.
Conditional Proposition - Uses the conditional operations.

p - Is called the hypothesis.
q - The conclusion.

Truth Table:
| Proposition | Proposition | Conditional|
| ----------- | ----------- | ---------- |
|      p      |      q      |    p → q   |
| ----------- | ----------- | ---------- |
            Truth Values:
|      T      |      T      |      T     |
|      T      |      F      |      F     |
|      F      |      T      |      T     |
|      F      |      F      |      T     |

Reasoning:
For instance "If you mow Mr. Smith's lawn, then he will pay you."
- Think of it as a contract.

False - Will only happen if you mow the lawn and he doesn't pay you, thus the contract is broken.
True - For any other situation, he can pay you or not.


EXERCISE: Understanding Conditional Statements.
- Given proposition r a conditional statement. Indicate the truth value is T/F.

1) r: If it rains today, I will have my umbrella. It is raining today. I do not have my umbrella.
- False, the hypothesis was that if it rains, YOU were SUPPOSED to have an UMBRELLA.
Since, you didn't meet the conclusion, you broke the agreement, leading to a FALSE truth value.


2) r: If Sally took too long getting ready, she missed the bus. Sally did not take too long getting ready. Sally missed the bus.
- True, this arguement was on the basis that if Sally took to long, she would miss the bus. However, she met
the same conclusion, either way and did not break the contract of lying and arriving on time with that hypothesis.

3) r: If it is sunny out, I ride my bike. It is not sunny out. I am not riding my bike.
- True, the argeement was that when it was sunny, you would HAVE to RIDE you bike. Since it wasn't sunny you didn't 
have too ride you bike either way it would have been true.

NOTE:
- THE ONLY possible manner in receiving a false truth value, is if the conclusion did not meet the truthful provided
hypothesis, such as 1).
- Any other different hypothesis or conclusion not in the pattern of "T then F" results in true as the initial
argeement wasn't broken.



English Expression of the Conditional Operation:
|       English         |               "p → q"                 |
| --------------------- | ------------------------------------- |
|     If p, then q.     | If you mow Mr. Smith's lawn, he will pay you.
-----------------------------------------------------------------------
|     If p, q.          | If you mow Mr. Smith's lawn, he will pay you.
-----------------------------------------------------------------------
|     q if p.           | Mr. Smith willl pay you if you mow his lawn.
-----------------------------------------------------------------------
|     p implies q.      | Mowing Mr. Smith's lawn implies that he will pay you.
-----------------------------------------------------------------------
|     q whenever p.     | Mr. Smith will pay you whenever you mow his lawn.
-----------------------------------------------------------------------
|     p only if q.      | You will mow Mr. Smith's lawn only if he pays you.
-----------------------------------------------------------------------
| p is sufficient for q | Mowing Mr. Smith's lawn is sufficient for him to pay you.
-----------------------------------------------------------------------
| q is necessary for p. | Mr. Smith's paying you is necessary for you to mow his lawn.


EXERCISE: Conditional Proposition from English Sentences:
- p: I will share my cookies with you.
- q: You will share your soda with me.

1) If you share you soda with me, then I share my cooke with you.
- "q → p".
The condition states when you share the soda, then the conclusion reaches to sharing the cookie.

2) Me sharing my cookie with you is sufficient for you to share your soda with me.
- "p → q"
The hypothesis is the cookie, the conclusion is the soda.

3) I will share my cookie with you only if you share your soda with me.
- "p → q"
Same hypothesis and conclusion, different wording.



Types of Conditional Statements:
- Each are representative of negation in different manners.

Converse: "p → q" is "q → p"

Contrapositive: "p → q" is "¬q → ¬p"

Inverse: "p → q" is "¬p → ¬q"


English Table:
| Proposition  |    p → q    | EX: If he studied for the test, then he passed the test.
| -----------  | ----------- | ---------- 
|   Converse   |    q → p    | If passed the test, then he studied for the test.
| -----------  | ----------- | ---------- 
|Contrapositive|   ¬q → ¬p   | If he did not pass the test, then he did not study for the test.
| ------------ | ----------- | ---------- 
|    Inverse   |   ¬p → ¬q   | If he did not study for the test, then he did not pass the test.








The Biconditional Operation:
- Denoted as "p ↔ q", it reads "p if and only if q".
- The proposition is true when both variables have the same truth value and false with different truth values.

Truth Table:
| Proposition | Proposition | Conditional|
| ----------- | ----------- | ---------- |
|      p      |      q      |    p ↔ q   |
| ----------- | ----------- | ---------- |
            Truth Values:
|      T      |      T      |      T     |
|      T      |      F      |      F     |
|      F      |      T      |      F     |
|      F      |      F      |      T     |


EXERCISE: Express conditional propositions using words and symbols:
1) r: If the contest is cancelled, then the band has practice today.

Statements are true:
- The contest is cancalled.
- The band does not have practice today.
ANS:
FALSE. The hypothesis remains true, meanwhile the conclusion is false, making this biconditional operation false
as both propositions aren't the same.


2) The variables are defined as follows:
- p: The weather is getting warmer.
- q: Flowers are blooming.
- r: The season is spring.

1) The weather is getting warmer if and only if blowers are blooming.
- 'p ↔ q'
(p) if and ONLY if (q), biconditional.

2) Flowers are blooming if the season is spring.
- 'r → q'
(r) if (q), conditional.

3) If the season is spring, then the weather is getting warmer.
- 'r → p'
(r) then (p), conditional.



3) The variables are defined as follows:
- p: The band does not have a contest today.
- q: The weather is snowy.
- r: The flight is not cancelled.

1) The flight is not cancelled and the weather is not snowy.
- 'r ∧ ¬q'
A conjunction with the use of AND, additionally only the second proposition was a negation.

2) If the band has a contest today, then the flight is not cancelled.
- '¬p → r'
A conditional with the use of THEN, additionally only the first proposition was a negation.

3) The weather is not snowy if and only if the band has a contest.
- '¬q ↔ ¬p'
A biconditional with the IF AND ONLY IF, also the first and second proposition was a negation.



4) Translate each proposition in the order written into a logical expression:
- p: The book is not well-written.
- q: Readers like the book.
- r: The book is not a bestseller.

1) The book being well-written implies that readers do not like the book or the book is a bestseller.
- '¬p → (¬q ∨ ¬r)'
(p) IMPLIES that ((NOT q) OR (NOT r))

2) If readers like the book, then the book is not a bestseller and the book is well-written.
- 'q → (r ∧ ¬p)'
(q) THEN (r AND (NOT p))

3) The book is a bestseller or the book is not well-written if readers do not like the book.
- '¬q → (¬r ∨ p)'
Start from IF (q) -> ((NOT r) OR (p))




Order of Operations:
Without parentheses to explicitly indicate the order of operations then:
1. ∧, ∨, and ¬
2. →, ↔

EX:
- p: Is true.
- q: Is true.
- r: Is false.
- s: Is false.

Identify the truth values of the following compound propositions.
1) s → q
- True, the contract remains true as long as the conclusion remains true to the initial hypothesis.

2) (r ↔ s) ∧ q
- True.
Firstly, the biconditional expression is read 'IF AND ONLY IF' in which both proposition must have the same
truth value to be true. (F AND F) == T, then and (conjunction) AND operator with T (q) results in true.

3) q → ¬r
- True.
The conditional expression remains true, as the conclusion remains true to the initial hypothesis.
Rather than lie/false to the initial hypothesis that would have resulted in false. Also the conclusion became true after negation.

4) (q ∧ s) → p
- True.
The conjunction of p and s results in false. However the conditional expression remains true as the conclusion remains
true to the hypothesis even if its false. The only manner for a conditional expression to become false is if the
conlusion becomes false to a true hypothesis.

5) (p ↔ r) ∧ (¬r ∧ ¬s)
- False.
Firstly ((NOT r) AND (NOT s)) results in a conjunction of T and T resulting in T.
Secondly (p IF AND ONLY IF r) results in a biconditional that can only be true if both propositions have the same 
truth value. ((T) IF AND ONLY IF (F)), which they don't results in F.
Lastly the final conjunction outside the parentheses for (F AND T) results in false.

6) q → ¬(r ∨ q)
- False.
Firstly the parentheses of (r OR q) becomes (F OR T) resulting in true by default of an existing true.
Secondly the negation of the parentheses, which turns true into false.
Lastly, the conditional in which the conclusion becomes false to its true hypothesis results in false.
As it broke it contract that IF (T) THEN (F), which the conclusion does not support the hypothesis results in false.




CHALLENGE: Truth Tables for Conditional Propositions.
1) Fill the truth table for proposition (¬p → q).
p | q | (¬p → q)
- | - | --------
T | T |    T 
T | F |    T
F | T |    T
F | F |    F

- The only why for a conditional expression to become false is if TRUE THEN FALSE.
In which it breaks the true hypothesis with providing a false conclusion, resulting in false.
Analogy, you work for 80 hours and your boss then pays you nothing (but was supposed too), the condition becomes false

REMINDER:
- The negation column isn't provided, manually think the inverse of the p column.


2) Fill the truth table for proposition p ∨ (¬p ↔ ¬q).
p | q | p ∨ (¬p ↔ ¬q)
- | - | --------
T | T |    T                    - ((NOT T) IF AND ONLY IF (NOT T)) == T -> (T OR T) = T 
T | F |    T                    - ((NOT T) IF AND ONLY IF (NOT F)) == F -> (T OR F) = T
F | T |    F                    - ((NOT F) IF AND ONLY IF (NOT T)) == F -> (F OR F) = F
F | F |    T                    - ((NOT F) IF AND ONLY IF (NOT F)) == T -> (F OR T) = T