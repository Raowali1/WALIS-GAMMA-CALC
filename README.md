Overview

This project is a calculator that computes both integer-order and fractional-order derivatives and integrals of polynomial expressions.
I made this as I'm being taught classical rules of calculus in highschool grade 12.
The tool is designed specifically for polynomial inputs and demonstrates how differentiation patterns can be extended into fractional orders through mathematical generalization.

Motivation

While studying patterns in derivatives of monomials, I noticed that repeated differentiation follows a pattern.
I likened it to the Permutations we were taught in Grade 11.
These Permutations allows us to break factorials into slices, which was perfect for high-order derivatives.
Each derivative introduces a multiplying factor based on the exponent.
The exponent decreases in a predictable pattern.
This observation led to the question of whether these patterns could extend beyond whole-number exponents.
From this, the idea emerged in my mind to push further.
I found an upgrade for this permutations factorial-based idea when I discovered the gamma function.
The gamma function does t have the limitation of deciamls sppoking it
In fact, when I changed my approach to gamma, I discovered that you can even input negative "orders" into the gamma function.
This turned out to be integration! A topic I hadn't even learned yet!
The project was developed as an independent exploration of these ideas using computational tools and self-directed learning.

Key Features

Differentiation of polynomials with integer and fractional exponents
Integration of polynomial terms with generalized exponent handling
Support for negative and non-integer powers

Mathematical Background

For standard integer powers, differentiation follows:
d/dx (xⁿ) = n xⁿ⁻¹
This pattern reflects a factorial-like structure when applied repeatedly.
To extend this idea beyond integers, the project uses concepts related to generalized factorials and the Gamma function:
n! = Γ(n + 1)
This allows extension of factorial-based differentiation to non-integer values, which is foundational in fractional calculus.
The implementation applies these generalized relationships at the level of polynomial terms, enabling consistent handling of fractional exponents.

Implementation Notes

Polynomial terms are processed individually and recombined
Uses algebraic rules for exponent manipulation
Designed for clarity and conceptual exploration rather than numerical optimization

Limitations

Only supports polynomial expressions
Does not handle transcendental functions like sinusoidal, exponential, or logarithmic
Fractional calculus implementation is still being tested to it's boundaries

Future Improvements
Extend support to more general functions beyond polynomials
Improve symbolic simplification of results
Add visualizations of fractional-order behavior
Optimize parsing for more complex expressions

Author Notes

This project was developed as an independent exploration of calculus patterns and their generalizations, supported by computational tools during the coding process.
The focus was on understanding how classical differentiation rules that I learned extend into fractional orders through factorials.
