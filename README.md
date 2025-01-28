# A two-sided type system with effects

A theory project extending off a [two-sided type system](https://arxiv.org/abs/2307.06928) to incorporate effects. A great introduction to the topic of type systems is Benjamin Pierce's [Types and Programming Languages](https://mitpress.mit.edu/9780262162098/types-and-programming-languages/).

## Abstract excerpt

Traditional type systems ensure that well-typed programs do not crash but offer no guarantees for programs that cannot be typed.

Two-sided systems provide two guarantees: well-typed programs do not go wrong, and ill-typed programs do not evaluate. The paper extends the two-sided system to track the effects and provide a more fine-grained expression of termination or evaluation.

**Types** describe _what_ values a program may evaluate to. **Effects** can describe _how_ a program evaluates to those values.

Effects can give us refined type information through enriching the types of our system with annotations and making any underlying side-effects or behaviour from computation explicit.
