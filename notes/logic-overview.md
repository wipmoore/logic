# Logic overview 

## Reasoning and Logic

Rationality is the quality or state of being rational, that is the being based on agreeable reason. It implies the conformity of ones beliefs with one's reason to believe and ones actions with ones reason for action.  Logic is the systematic study of the form of an argument.


## Properties of a system of logic

- Completeness : If a formula is true it can be proven in the system
- Consistency  : No theorem contradicts another theorem in the system
- Expressive   : The breadth of concepts that can be expressed in the system
- Soundness    : If an formula is theorem of the system it is true.
                 This is the convers of Completness
- Validity     : Valid formulas can not make false inferences from true premises

## Semantics

The validity of an argument depends on the meaning ( semantics ) of the sentences that make it up.

Note - This is quite and in depth concept.


## Inference and Implication

Inference consists of two separately asserted propositions of the form 'p therefore q', it is not true or false but valid or invalid.  An implication is a sentence of the form 'If p then q' and can be either true or false.  There is a connection between inference and implication if the implication 'If p then q' is true the inference 'p therefore q' is valid.  To create a sound argument you need to demonstrate the implication that the inferences within your argument have been built upon.


## Types of logic

- Syllogistic
- Propositional
- Predicate
- Modal


### Syllogistic

This is an approach to logic based on the ideas of Aristotle and is widely regarded as only having historical significance now.


### Propositional

Is a formula system in which formulae representing propositions can be formed from combining atomic propositions using logical connectives and in which a system of formal proof rules establish certain formula as theorems.


### Predicate

Extends Proposition logic to include quantifiers which are general enough to include a wide set of arguments occurring in natural language.  

e.g.

There is a man who shaves all and only men who do not shave themselves.

(∃x)(man(x) ∧ (∀y)(man(y) → (shaves(x,y) → ¬shaves(x,x)))


#### First-order logic

First order logic uses quantified variables over non logical objects and allows the use of sentences that contain variables.  So rather than propositions such as 'Socrates is a man' you express in the form 'there exist x such that x is Socrates and x is a man.  There exist is a quantifier.


#### Second-order logic

Is an extension to first order logic, in first order logic quantifies only qualify variable that range over an individual in second order logic allows quantifiers over relations.  e.g. ∀P∀x( x ∈ P ∨ x ∉ P ) for every unary relation P of individuals and every individual x either x is in P or it is not.  This is the basis for type theory.


### Modal

In language modality deals with the phenomenon that sub parts of a sentence may have their semantics modified by special verbs or modal particles.  e.g. 'We go to the games' can be modified to give 'We should go to the games'.  It modified the circumstances in which we take an assertion to be satisfied.

∀ - 2200
∃ - 2203
∧ - 2227
∨ - 2228
→ - 2192
¬ - 00ac
∈ - 2208
∉ - 2209
