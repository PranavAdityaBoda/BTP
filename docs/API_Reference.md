# BTP API Reference
## Modules
### pp_binomial.py
Generates all possible binomials for a given polynomial degree. Key functions/classes:
* `generate_binomials(degree)`, generates all possible binomials for a given polynomial degree
* `get_polynomial(degree)`, returns a polynomial of a given degree

### pp_check.py
Checks if a given polynomial is a permutation polynomial by verifying its roots. Key functions/classes:
* `is_permutation_polynomial(poly)`, checks if a given polynomial is a permutation polynomial
* `verify_roots(poly)`, verifies the roots of a given polynomial

### sage_time.py
Checks if a given polynomial is a permutation polynomial by verifying its roots. Key functions/classes:
* `check_permutation(poly)`, checks if a given polynomial is a permutation polynomial using Sage
* `time_verification(poly)`, times the verification of a polynomial's roots

### pp1.py
**pp1.py** is a key module in the BTP repository. Key functions/classes:
* `binaryToPolynomial(binary)`, converts a binary string to a polynomial
* `apply_polynomial(poly)`, applies a polynomial to a given input

## Quick Reference
| Symbol | Description |
|--------|-------------|
| `binaryToPolynomial` | Converts binary string to polynomial |
| `generate_binomials` | Generates all possible binomials for a given polynomial degree |
| `is_permutation_polynomial` | Checks if a given polynomial is a permutation polynomial |
| `check_permutation` | Checks if a given polynomial is a permutation polynomial using Sage |