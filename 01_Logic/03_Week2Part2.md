03 - Week 2 Part 2:

Predicates: Statements with Variables
Predicate - Is like a statement, but its truth value depends on one or more variables.
- Becomes a proposition only when plugging in specific values for its variables.
- Without a value, its truth is undetermined.
- Fill-in-the-blank statement.

EX: Single Variable
Predicate: P(x): "x is a prime number"
P(x) by itself is not true or false. We need to know what x is.

|   Substitute  |       Becomes         |     Truth Value
----------------|-----------------------|-------------------
|     P(4)      | "4 is a prime number" |     False  
|     P(5)      | "5 is a prime number" |     True
|     P(7)      | "7 is a prime number" |     True
|     P(9)      | "9 is a prime number" |     False


EX: Multiple Variables
Predicate: Q(x, y): "x + y = 7"

|   Substitute  |       Becomes         |     Truth Value
----------------|-----------------------|-------------------
|   P(4, 3)     |   "4 + 3 = 7"         |     True  
|   P(3, 2)     |   "3 + 2 = 7"         |     False
|   P(0, 7)     |   "0 + 7 = 7"         |     True


Combining Predicates with Operators:
- Once a predicate has values plugged in, it is a proposition. Then combine the proposition with operators
Using Q(x, y): "x + y = 7"

- Q(4,3) V Q(3,2): "4 + 3 = 7 OR 3 + 2 = 7" -> True V False = True
- Q(4,3) ∧ Q(3,2): "4 + 3 = 7 AND 3 + 2 = 7" -> True ∧ False = False
- ¬Q(4,3): "NOT (3 + 2 = 7)" -> True


Why Predicates Matter in CS:
• Database Queries: WHERE age > 18 is the predicate "age > 18"
• Filter Functions: lambda x:x > 0 in Python is a predicate.
• Loop conditions: while (i < n) checks a predicate every iteration.
• Type Checking: isinstance(x, int) is a predicate on x.
• Validation: "is this email format correct" is a predicate.

- Almost every condition qualifies as a predicate. Since its logic is just the math language for these conditions.








Universal & Existential Quantifiers:
- Notice that P(x) isn't a proposition until a value is plugged in.
- Another manner to make it a proposition is using a quantifier.

Quantifiers - Describe how much of the domain makes a predicate true.
• Universal Quantifier (∀): "For all"
• Existential Quantifer (∃): "There exists"

- The domain (set of possible values) THAT DETERMINES what x can be.



Universal Quantifier (∀):
∀x P(x) - P(x) is true for every value of x in the domain.
English equivalent: every, all, each, any.

Domain: Positive Integers:
• ∀x (x > 10): "All positive integers are greater than 10" -> FALSE (1, 2, ..., 10) are positive.
• ∀x (x > 0): "All positive integers are greater thann 0" -> TRUE, anything below 0 aren't positive.

To DISPROVE a universal: Find one counterexample.



Existential Quantifer (∃):
∃x P(x) - AT LEAST ONE value of x is in the domain for which P(x) is true.
English equivalent: some, there exists, at least one.

Domain: Positive Integers:
• ∃x (x < 0): "There is a positive integer less than 0" -> False, anything below 0 isn't positive.
• ∃x (x > 10): "There is a positive integer greater than 10" -> True, there are positive ints above 10.

To PROVE an existential: Find one example.



Proving and Disproving: Cheat Sheet

        To...           |             ∀x P(x) (universal)           |               ∃x P(x) (existential)
    PROVE true          |       Show P(x) holds for every x         |       Find one x where P(x) holds
    DISPROVE            |       Find one counterexample             |       Show P(x) fails for every x


NOTE:
- Universal is HARD to prove (as you must check all) but EASY to disprove (one bad case).
- Existential is the opposite.


Practice: True or False?
Domain: All positive integers {1,2,3, ...}
1. ∀x (x² = x)

English Equivalent: All positive integers are equivalent to their squared version?
ANS: FALSE, (2^2 == 2), two squared does not equal to 2. Only true for x = 1.

2. ∀x (x² > x)
English Equivalent: All positive integers are less then their squared version?
ANS: FALSE, (1^2 == 1), squared one isn't greater than 1, its equal. Only true for any value after 1.

3. ∀x (x² ≥ x)
English Equivalent: All positive integers are less than or greater than their squared version?
ANS: TRUE, (1^2 == 1), squared one is NOW equal to 1. Therefore this proposition is true for all the domain.

4. ∃x (x² = x)
English Equivalent: At least one positive integer is equivalent to their squared version?
ANS: TRUE, (1^1 == 1), integer one is the only value that is equivalent to thier square version.

5. ∃x (x² < x)
English Equivalent: At least one positive integer is greater than their squared version?
ANS: FALSE, (1^1 == 1), every other integer is less than their squared version. Also one would be the
only integer equivalent, but none are greater.









Negating Quantified Statements:

De Morgan's Law for Quantifiers:
- Negating a quantifier flips it: (∀ becomes ∃, ∃ becomes ∀) and pushes the negation onto the predicate.

Rule 1:
¬∀x P(x) = ∃x ¬P(x)

Rule 2:
¬∃x P(x) ≡ ∀x ¬P(x)


Why it Works: English Intuition:
Rule 1 in plain English:
• "NOT every x has property P"
- means
• "There EXISTS an x without property P"


Rule 2 in plain English:
• "There is NO x with property P"
- means
• "Every x lacks property P"


Example: Students at School
Domain: Students in a school, E(x): "x is enrolled in this class"

Negate: "every student enrolled"
• Original: ∀x E(x)
• Negation: ¬∀x E(x) = ∃x ¬E(x)
• In English: "At least one student is not enrolled"


Negate: "some student is enrolled"
• Original: ∃x E(x)
• Negation: ¬∃x E(x) = ∀ ¬E(x)
• In English: "No student is enrolled"



Pushing Negation Inward:
- Standard Form