# Piecewise-Polynomials and Splines Quiz

## 7.2.R1

Why are natural cubic splines typically preferred over global polynomials of degree d?

- Polynomials have too many degrees of freedom
- **Polynomials tend to extrapolate very badly**
- Polynomials are not as continuous as splines

## 7.2.R2

Let 1\{x \leq t\} denote a function which is 1 if x \leq t and 0 otherwise.

Which of the following is a basis for linear splines with a knot at t? Select all that apply:

- **1, x, (x - t)1\{x > t\}**
- **1, x, (x - t)1\{x \leq t\}**
- 1\{x > t\}, 1\{x \leq t\}, (x - t)1\{x > t\}
- **1, (x - t)1\{x \leq t\}, (x - t)1\{x > t\}**