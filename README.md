# solve_string

<h4 align="center" valign="middle">
Get notified about updates and join us at ‎‎<a href="https://discord.gg/jjsFjTp">
        <img valign="middle" src="https://img.shields.io/discord/765231762208063509"
            alt="chat on Discord">
</a>
</h4>

<h3>
  About:
</h3>
A python eval equivalent written in rust. 
This software is in ALPHA. Tons of edge cases will not work and some things like imaginary numbers have yet to be implemented.

<h3>
Current support:
</h3>

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


<h3>
Known issues:
</h3>

- *multiplication without a operator, ie 9(5 + 1), fails.
- No unit tests
- negative number edge cases: report and document these if you find them.
- imaginary numbers.
- precision greater than f32.

Feel free to open a issue or pull request, I am happy to work with you to get supported for any feature requests. The current plan is solve the issues in the order they are above.
