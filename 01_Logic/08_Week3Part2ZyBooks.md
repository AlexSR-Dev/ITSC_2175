08 - Week3Part2yBooks


2.1: An Introduction to Boolean Algebra:

Boolean Algebra - A set of rules and operations for working with variables with values that are 0 or 1.
- The value 1 corresponds to T in the rules of propositional logic, and the value 0 corresponds to F.
- Basically a reworded version of logical operations.


Boolean Multiplication - denoted by '*', applies two elements from {0,1}, basically ∧ (and) operation.

Boolean *       |   Logical ∧
------------------------------
0 * 0 = 0       |   F ∧ F = F
0 * 1 = 0       |   F ∧ T = F
1 * 0 = 0       |   T ∧ F = F
1 * 1 = 1       |   T ∧ T = T

Boolean Addition - denoted by '+', applies to the two elements {0,1}, however the results cannot exceed 0 or 1. V (OR) operation.

Boolean +       |   Logical V
-----------------------------
0 + 0 = 0       |   F V F = F
0 + 1 = 1       |   F V T = T
1 + 0 = 1       |   T V F = T
1 + 1 = 1       |   T V T = T


Complement, denoted by a bar symbol on top of the value, reverses the element's value. NOT operator "¬".

Boolean Complement  |   Logical ¬
---------------------------------
-                   |
0 = 1               |   ¬F = T

-                   |
1 = 0               |   ¬T = F



---         ---         ---         ---         ---         ---         ---         ---
TEST NOTE: (HAVE NOT verified through slides/class assignments yet)
(*) - AND operator.
(+) - OR operator.
(-) - NOT operator.

These boolean algebra, only corresponds with variables whose values are ONLY 0 or 1.
---         ---         ---         ---         ---         ---         ---         ---


Boolean Variable - variables that can have a value of 1 or 0.
Boolean Expression - Built up by applying Boolean operations to Boolean variables or the constants 1 or 0.
EX: 0 * (0 + 1) = 0

Precedence Rules for Boolean Operations:
1. - Parentehese overrides precedence rules.
2. - Complement applied. 
3. - *
4. - +


NOTE:
These Boolean expression can use compact expression such as XY = X * Y.


2.1.3: Boolean Expression Evaluation
- Give the value for each Boolean expression. Use the following values for the variables:
x = 0, y = 1, z = 1.

1) (x + (-y))z
- (-y) = 0, x = 0, z = 1
- (0 + 0) = 0
- 0 * 1 = 0
x + (-y))z = 0


2) x + yz
- x = 0, y * z  == 1 * 1 -> 1
- 0 + 1 = 1
x + yz = 1


3) (x + y)(-z + (-1))
- x = 0, y = 1, -z = 0, -1 = 0
- (x + y) == (0 + 0) = 0
- (-z + (-1)) == (0 + 0) = 0
- 0 * 0 = 0
(x + y)(-z + (-1)) = 0


4) -(z(x + y))
- z = 1, (x + y) == (0 + 1) = 1
- z(1) == 1 * 1 = 1
- -(1) = 0
-(z(x + y)) = 0





- Like logical expression, two boolean expressions are equivalent if they have the same value for every possible combination of values assigned to the variables contained in the expression


Laws of Boolean Algebra:

Laws                        |               Addition (OR)                         |         Multiplication (AND)      
-------------------------------------------------------------------------------------------------------------------------------------
Idempotent Laws:            |                 x + x = x                           |             x * x = x        
-------------------------------------------------------------------------------------------------------------------------------------
Associative Laws:           |           (x + y) + z = x + (y + z)                 |           (xy)z = x(yz)
-------------------------------------------------------------------------------------------------------------------------------------
Commutative Laws:           |               x + y = y + x                         |               xy = yx
-------------------------------------------------------------------------------------------------------------------------------------
Distributive Laws:          |           x + yz = (x + y)(x + z)                   |             x(y + z) = xy + xz
-------------------------------------------------------------------------------------------------------------------------------------
Identity Laws:              |                 x + 0 = x                           |             x * 1 = x
-------------------------------------------------------------------------------------------------------------------------------------
Domination Laws:            |                 x + 1 = 1                           |             x * 0 = 0
-------------------------------------------------------------------------------------------------------------------------------------
Double Complement Law:      |                 x̿ = x                               |
-------------------------------------------------------------------------------------------------------------------------------------
Complement Laws:            |               x + -x = 1                            |             x(-x) = 0
                            |               -0 = 1                                |             -1 = 0
-------------------------------------------------------------------------------------------------------------------------------------
De Morgan's Laws:           |             -(x + y) = (-x)(-y)                     |             -(xy) = (-x + -y)
-------------------------------------------------------------------------------------------------------------------------------------
Absorption Laws:            |             x + (xy) = x                            |               x(x + y) = x
-------------------------------------------------------------------------------------------------------------------------------------





2.1.5: Equivalent Boolean Expression

1) -(x + y)(z + -x)
- De Morgan's law:
((-x)(-y)) (z + -x)

2) (-y + -z)x
- Distributive law:
(-yx) + (-zx)

3) y(x + -x)
- Complement law:
y(1)
- Identity Law:
y * 1 = y



2.1.6: Proof Two Boolean expresssions are equivalent 1:

x + -(xy)

1) x + (-x + -y)       De Morgan's Law
2) (x + -x) + -y       Associative Law
3) 1 + -y              Complement Law
4) -y + 1              Commutative Law
5) 1                   Domination Law


2.1.7:

x((-x + y)(-(xz))) == xy(-z)

1. x((-x + y)(-x + -z))       De Morgan's Law

2. x(-x + y(-z))              Distributive Law

3. x(-x) + xy(-z)             Distributive Law

4. 0 + xy(-z)                 Complement Law

5. xy(-z) + 0                 Commutative Law

6. xy(-z)                     Identitiy Law



2.1.1:

(-x)(x + -y)(x + z) == (-(x + y))z

1. (-x)(x + -yz)            Distributive Law

2. -xx + -x-yz              Distributive Law

3. 0 + -x-yz                Complement Law

4. -x-yz                    Identity Law

5. (-(x + y))z              De Morgan's Law



2.1.2: Boolean Expressions:

1) Find the value for each Boolean Expression.
For the variables: x = 0, y = 1

(1) -y = 0
- -(1) == 0
(2) xy = 0
- 0 AND 1 == 0


2) Find the value for each Boolean Expression.
For the variables: x = 1, y = 1

(1) -(x + y) = 0
-( 1 OR 1) == -(1) = 0

(2) -x + -y = 0
- -(1) OR -(1) == 0 OR 0 = 0


3) Find the value for each Boolean Expression.
For the variables: W = 0, x = 0, y = 0, z =1

(1) -(wx) + y + -z = 1
- -(0 AND 0) OR 0 OR -(1)
- -(0) OR 0 OR 0
- 1 OR 0 OR 0
- 1 OR 0 = 1

(2) (1 + -x)(1 + y)(-z) = 0
- (1 OR -(0)) (1 OR 0) (-1)
- (1 OR 1) (1 OR 0) (0)
- 1 AND 1 AND 0
- 1 AND 0 = 0


(4) The following proof shows: -(z + -(x)) + -(z + y) == -z(x + -(y))

-(z + -(x)) + -(z + y)

1. -(z-(x)) + -(z + y)           De Morgan's Law

2. (-z)x + -(z + y)              Double Complement Law
                                 - Initially, -(z-(x)) => -z * --x, thus with double complement law
                                 it becomes => -z * x.

3. (-z)x + -(zy)                De Morgan's Law

4. -z(x + -(y))                 Distributive Law
                                - Initially, (-z)x + -(zy), and since -(zy) == (-z * -y), then we redistribute -z resulting in: -z(x + -(y))

                                   