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
