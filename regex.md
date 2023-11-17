# regexTut

Introductory tutorial on Matching Email regex

## Summary

In this tutorial, we will be exploring a regular expression designed to match email addresses. 
The regex is /^([a-z0-9_\.-]+)@([\da-z\.-]+)\.([a-z\.]{2,6})$/. 
We'll break down each component of the regex and explain how it validates email addresses.

## Table of Contents

- [Anchors](#anchors)
- [Quantifiers](#quantifiers)
- [Grouping Constructs](#grouping-constructs)
- [Bracket Expressions](#bracket-expressions)
- [Character Classes](#character-classes)
- [The OR Operator](#the-or-operator)
- [Flags](#flags)
- [Character Escapes](#character-escapes)

### Anchors
    ^: Asserts the start of the string.
    $: Asserts the end of the string.

### Quantifiers
    +: Matches one or more occurrences of the preceding element (one or more characters in this context).
    {2,6}: Matches between 2 and 6 occurrences of the preceding element (used for the TLD part).

### Grouping Constructs
    (...) is used for grouping constructs to capture parts of the pattern.

### Bracket Expressions
    [a-z0-9_\.-]: Matches any lowercase letter, digit, underscore, dot, or hyphen (used for the username part).
    [\da-z\.-]: Matches any digit, lowercase letter, dot, or hyphen (used for the domain part).
    [a-z\.]: Matches any lowercase letter or dot (used for the TLD part).

### Character Classes
    \d: Matches any digit.

### The OR Operator
    |: The OR operator is not explicitly used in this regex.

### Flags
    No flags are specified in this regex.

### Character Escapes
    \.: Escapes the dot to match a literal dot.

## Author

This tutorial was created by Yehudah Christian.