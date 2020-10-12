# solve_string
A python eval equivalent written in rust. 
This software is in ALPHA. Tons of edge cases will not work and some things like imaginary numbers have yet to be implemented.

Current support:

- multiple operators written solved in pemdas.

- operators supported:

- - subtraction *-* or ~ 
- - multiplication * 
- - addition + 
- - division / 
- - exponent ^ 

- currently there is not root operator, however you can use a exponent fraction in place of one.

- double negatives

- Parenthesis are supported*

Known issues:

- multiplication without a operator, ie 9(5 + 1).
- No unit tests
- negative number edge cases: report and document these if you find them.
- imaginary numbers.
- precision greater than f32.

Feel free to open a issue or pull request, I am happy to work with you to get supported for any feature requests. The current plan is solve the issues in the order they are above.
