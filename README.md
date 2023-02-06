# Title (REG X paper)

Introductory paragraph (A regex, is a sequence of characters that defines a specific search pattern. )

## Summary

Regular expressions, or regex for short, are a series of special characters that define a search pattern. Take the following example of a regular expression, which we’ll call “Matching a Username”:  /^[a-z0-9_-]{3,16}$/

## Table of Contents

- [Anchors](#anchors)
- [Quantifiers](#quantifiers)
- [Grouping Constructs](#grouping-constructs)
- [Bracket Expressions](#bracket-expressions)
- [Character Classes](#character-classes)
- [The OR Operator](#the-or-operator)
- [Flags](#flags)
- [Character Escapes](#character-escapes)

## Regex Components

### Anchors
Anchors are regex tokens that don't match any characters but that say or assert something about the string or the matching process. Anchors inform us that the engine's current position in the string matches a determined location.

### Quantifiers
Quantifiers specify how many instances of a character, group, or character class must be present in the input for a match to be found.

### Grouping Constructs
Grouping constructs delineate the subexpressions of a regular expression and capture the substrings of an input string.

### Bracket Expressions
Brackets indicate a set of characters to match. Any individual character between the brackets will match, and you can also use a hyphen to define a set.

### Character Classes
A character class is a set of characters enclosed within square brackets. It specifies the characters that will successfully match a single character from a given input string.

### The OR Operator
Alternation is the term in regular expression that is actually a simple “OR”. In a regular expression it is denoted with a vertical line character | .

### Flags
A regular expression consists of a pattern and optional flags: g , i , m , u , s , y . Without flags and special symbols (that we'll study later), the search by a regexp is the same as a substring search. 

### Character Escapes
The \ is known as the escape code, which restore the original literal meaning of the following character. It indicates a single whitespace character.

## Author
Maddrick Long based out of Atlanta, Ga. 
https://github.com/Drip101/Regular-X-paper
