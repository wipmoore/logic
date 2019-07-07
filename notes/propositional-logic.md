# Propositional logic 

## Propositions

Is a fact that has a truth value, it is either true or false.  x + 3 = 10 is not a proposition because it is not a statement, it is true for some values of x while false for others.  This statement is false is not a proposition it is a paradox.


## Negation

- It is not the case that <statement>
- ¬ ~ -
-   P : New Delhi is the capital of India
   ¬P : It is not the case that New Delhi is the capital of India

|  P  | ¬P  |
|-----|-----|
|  T  |  F  |
|  F  |  T  |


## Conjunction ( ∧ )

- Conjunction is the action or instance of two or more events occurring at the same point in time.
- e.g. For admission to IIT for Mtech you should pass Btech with sixty percent _and_ pass the gate exam
    - P : Pass Btech with sixty percent
    - Q : Pass the gate exam

    - Admission : P ∧ Q

|  P  |  Q  |  P∧Q  |
|-----|-----|-------|
|  T  |  T  |   T   |
|  T  |  F  |   F   |
|  F  |  T  |   F   |
|  F  |  F  |   F   |


## Disjunction ( ∨ )

- Disjunction a lack of correspondence or consistency. It is the relation of two distinct alternatives.
- To get a pension you should be at least sixty years old _or_ have twenty years service.
    - P : You are sixty years old
    - Q : You have twenty years service

    - Pension : P ∨ Q

|  P  |  Q  |  P∧Q  |
|-----|-----|-------|
|  T  |  T  |   T   |
|  T  |  F  |   T   |
|  F  |  T  |   T   |
|  F  |  F  |   F   |


## Exclusive Or ( ⊕ )

- On a treadmill you can either walk or run
    - P : You are walking
    - Q : You are running

    - treadmill : P ⊕ Q

|  P  |  Q  |  P∧Q  |
|-----|-----|-------|
|  T  |  T  |   F   |
|  T  |  F  |   T   |
|  F  |  T  |   T   |
|  F  |  F  |   F   |


## Implication ( → )

- If you work for ten hours a day then you get a bonus
    - P : You work for ten hours in a single day
    - Q : You get a bonus

    - bonus : P → Q

|  P  |  Q  |  P → Q  |
|-----|-----|---------|
|  T  |  T  |    T    |
|  T  |  F  |    F    |
|  F  |  T  |    T    |
|  F  |  F  |    T    |


### Implication Analysis

1. General

- Antecedent  : A things the exist before or logically precedes another.
- Consequent  : Following as a result or effect.

- if P then Q
- P implies Q

2. Dependency

- Q is necessary for P
- P is sufficient for Q

- Necessary
    - Q only if P
    - If P is necessary for Q then Q can not be true unless P is true

- Sufficient
    - If P is sufficient for Q then If you have P then you have Q

An implication means the following properties hold true:
    - The consequent is necessary for the antecedent to be true.
    - The antecedent is sufficient for the consequent to be true.

You are asserting that if you have the antecedent you will have the consequent but if you have the consequent it does not mean that you have the antecedent, there may be other conditions that result in the antecedent being true.


## Logical Operators

In order of precedence 

- () Parenthesis
- ¬  Not
- ∧  And 
- ∨  Or
- →  Implication
- ↔  Material Implication


## Truth tables 

The height of the truth table for an expression is dependent on the number of variables.  2^n when n is the number of variables.  The width of a truth table is based on the number of expressions once the ambiguity has been removed.

e.g.
- P ∨ ¬Q  = (P ∨ (¬Q))


## Tautology

- A tautology is an expression that is always true.
- (P ∨ Q)  ∨ (¬Q)

|  P  |  Q  | ¬Q  | P∨Q | (P∨Q) ∨ ¬Q |
|-----|-----|-----|-----|------------|
|  T  |  T  |  F  |  T  |     T      |
|  T  |  F  |  T  |  T  |     T      |
|  F  |  T  |  F  |  T  |     T      |
|  F  |  F  |  T  |  F  |     T      |


## Contradiction  

- A contradiction is an expression that is always false.
- P ∧ ¬P

|  P  | ¬P | P ∧ ¬P |
|-----|----|--------|
|  T  |  F |   F    |
|  F  |  T |   F    |


## Contingency 

- A statement that is sometimes true and sometimes false
- P ∨ ¬Q


|  P  |  Q  | ¬Q  | (P∨Q) ∨ ¬Q |
|-----|-----|-----|------------|
|  T  |  T  |  F  |      T     |
|  T  |  F  |  T  |      T     |
|  F  |  T  |  F  |      F     |
|  F  |  F  |  T  |      T     |


## Satisfiable

A compound proposition is satisfiable if there is an assignment of truth values ( true or false ) to its variables such that it makes it true.


## Unsatisfiable

A compound proposition is unsatisfiable if every assignment of truth values to its variables result in the proposition being false.


## Logical equivalence

If you have an expression with n variables the maximum number of outcomes is 2^n.  The compound propositions P and Q are called logically equivalent if P ↔ Q is a tautology.  Basically this mean that you can have an unlimited number of formula in a compound proposition but the outcomes can only be 2^n.  Two compound propositions P and Q are logically equivalent if they have the same truth table.


## Identity

- P ∧ T ≡ P
- P ∨ F ≡ P


## Domination

- P ∧ F ≡ F
- P ∨ T ≡ T


## Idempotent

- P ∨ P ≡ P
- P ∧ P ≡ P


## Negation

- P ∨ ¬P ≡ T
- P ∧ ¬P ≡ F


## Involution

- ¬(¬P) ≡ P


## Commutative

- P ∨ Q ≡ Q ∨ P
- P ∧ Q ≡ Q ∧ P


## Distributive

- P ∧ (Q ∨ R) ≡ (P ∧ Q) ∨ (P ∧ R)
- P ∨ (Q ∧ R) ≡ (P ∨ Q) ∧ (P ∨ R)


## Associative

- P ∧ (Q ∧ R) ≡ (P ∧ Q) ∧ R
- P ∨ (Q ∨ R) ≡ (P ∨ Q) ∨ R

## Symbols unicode references

∀ - 2200
∃ - 2203
∧ - 2227
∨ - 2228
→ - 2192
¬ - 00ac
∈ - 2208
∉ - 2209
⊕ - 2295
→ - 2192
↔ - 2194
≡ - 2261
