# First order logic 

_P(x) : x is a girl_

- P(x)          : predicate function
- x             : variable
- x is a girl   : predicate function behaviour

A predicate function is an open statement so has no truth value.  Instances of a predicate function ( the function applied to a value ) have a truth value. 

e.g. 

- Rami  is a girl
- Radha is a girl
- Rami  is a girl

Predicates can be combined:

- P(x) ∧ Q(x)
- P(x) ∨ Q(x)

Predicates follow the logical equivalence rules.


## Domain of discourse

Is the set of objects over which a variables may range in a formal treatment.


## Quantifiers

Specify the quantity of the specimens in the domain of discourse.  A quantified expression is one where the free variables of a predicate statement is bound by a quantifier.


## Universal quantifier ( ∀ )

- ∀x    : x is a fruit

Says that all members of the domain of discourse are fruit.

- S         : { a,b,...,z }
- ∀xP(x)    ≡ P(a) ∧ P(b) ∧ ... ∧ P(z) 


## Existential quantifier ( ∃ )

- ∃x    : x is a fruit

Says that there is at least one element in the domain of discourse that is a fruit.

- S         : { a,b,...,z }
- ∃xP)x)    ≡ P(a) ∨ P(b) ∨ ... ∨ P(z) 


## Order of predicates 

- ∀x ∃y P(x, y) 

This says that for all members of the domain of discourse the is at least one member of the domain of discourse that will allow the predicate P to hold.

- ∃x ∀y P(x, y)

This says there is at least one member of the domain of discourse that for all members of the domain of discourse the predicate P will hold.


## Compound statements

- Every city in India is clean:
    - city  : { Delphi, Hydenabad, Florida, Bay of Bengal }
    - C(x)  : x is a city in India
    - L(x)  : x is a clean city
    - ∀x [C(x) → L(x)]
        - for all x if x is a city in india then it is clean.

    - where city is the definition of the domain of discourse.

- Some days are holidays:
    - Days  : { Diwali, Christmas Day, Monday }
    - D(x)  : x is a day
    - H(x)  : x is a holiday
    - ∃x [D(x) ∧ H(x)]
        - for at least one x if x is a day then x is also a holiday

    - where Days is the definition of the domain of discourse.


- __∀__ can only use the __→__ connective.
- __∃__ can only use the __∧__ connective.


## Quantifying predicate functions

Associating a predicate function with a quantifier makes it a predicate statement which can be assigned a truth values.

- ∀P(x)
- ∃P(x)


## Equivalence with quantifiers

- ¬∀xP(x) ≡ ∃x¬P(x)
    - Not every x is a P __or__ there is at least some x that is not P

- ¬∃xP(x) ≡ ∀x¬P(x)
    - No x is a P __or__ all x are not P

- ∀(R ∧ I) ≡ ∀R ∧ ∀I
- ∃(R ∧ I) ≢ ∃R ∧ ∃I

- ∀(R ∨ I) ≢ ∀R ∨ ∀I
- ∃(R ∨ I) ≡ ∃R ∨ ∃I

- ∀(R ↔ I) ≢ ∀R ↔ ∀I
- ∃(R ↔ I) ≢ ∃R ↔ ∃I


## Symbols Unicode references

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
≢ - 2262
′ - 2032
⇒ - 21d2
↑ - 2191
↓ - 2193
∀ - 2200
∃ - 2203
