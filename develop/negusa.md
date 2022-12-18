# NEGUSA-NAGAST_regex

redex for URL:
/^(https?:\/\/)?([\da-z\.-]+)\.([a-z\.]{2,6})([\/\w \.-]*)*\/?$/
a regex is a sequence of characters that defines a search pattern that can be used to validate user input. i will brake this down in my tutorial brake down.

## Summary
im using the URL regex for this example, we will brake it down by its components (anchor, quantifies, grouping constructs, bracket expressions, character classes, and character escapes). each one is replaced with a symbol to say. the code is found inside of the regex.

## Table of Contents

- [Anchors](#anchors)
- [Quantifiers](#quantifiers)
- [grouping and constructs](#grouping-and-capturing)
- [bracket expressions](#bracket-expressions)
- [character-classes](#character-classes)


## Regex Components
### Anchors
.symbol 
^
 $

.descritons

1. Asserts the position at the start of the string.
2. Asserts the position at the end of the string.

.regex code
``/^(h`
`/?$/``
### Quantifiers
.symbol 
?
(*)
(+)
{2,6}

.descritons

1. matches 0-1 also you can do it as many times as possible.
2. Matches the prevoius token between 0 and unlimited times.
3. between 1 and ulimited times.
4. between 2 and 6 times, as many times as possible.

.regex code
(https?:\/\/)?
([\/\w \.-]*)*
([\da-z\.-]+)
([a-z\.]{2,6})


### Character Classes
.symbol
\d
\w

.descripton
1. one character that is a digit.

2. matches any word character.

.regex code
([\da-z\.-]+)
[\/\w \.-]
### Grouping and Capturing
.symbol
(?:...)

.description
1. Matches everything enclosed.

.regex code
(https?:\/\/)?
### Bracket Expressions
.symbol
[a-z]
[\/ \w\.-]

.description
single character a-z.

a single character on the list. (regex code)

.regex code
[a-z\.] is the code if your just working with a-z. [\da-z\.-] is the code if your working with a-z before one digit equivalent to [0-9].

\/ = matches the character /
\w = matches any word character equivalent to [a-zA-Z0-9_]
\. = matches the character .
- = matches the character -

## Author