# Delimiter-Matching-using-restricted-structures
This (code checks {if the inputted} text has matching delimiters).


This repository is a java code that checks for the delimiters in a line of a text typed by the user. The text that some delimiters like ( ) { } [ ], the code then 
checks if the opening and closing delimiters matchs. If it does, it returns "All Delimiters Matches" if they match and "Not matched" if they don't match.

c[d]          // All Delimiters Matches
a{b[c]d}e     // All Delimiters Matches
a{b(c]d}e     //Not matched
( a[b{c}d]e}  //Not matched
