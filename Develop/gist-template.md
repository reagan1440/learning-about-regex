# Understanding Regular Expressions in JavaScript

Regular expressions (regex) a combination of alphabets, numbers and special characters are powerful tools used for pattern matching and text manipulation in JavaScript. Throughtout this guide we will learn the basics of Regex and various components and concepts to help use regex more effeciently 

## Summary

In this guide we will learn the basics of regular expressions in JavaScript and explain components such as anchors, quantifiers, grouping constructs, bracket expressions, charcter classes, flags, and charcter escapes. Throught the lesson code snippets will be provided as well as explanations to help the ready apply regex in their code

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
## Anchors
Anchors such as '^' and '&' match the position of text in a string, such as the start('^') or end ('&') of a line 
// example: match a string with "hello"
const regex = /^hello/;
![Alt text](<images/Screenshot (12).png>)

### Quantifiers
quantifiers like '*', '+', '?' and '{}' specify the number of occurrences of a charcter or group in a pattern.
// example: match digits occurring 2 or 3 times
const regex = /\d{2,3}/;
![Alt text](<images/Screenshot (14).png>)

### Grouping Constructs
parentheses '()' create capture groups and allow you to apply quantifiers and other operations to a group of charcters
// example: match words starting with either "hello" or "world"
const regex = /(hello|world)\w+/;
![Alt text](<images/Screenshot (15).png>)

### Bracket Expressions
bracket expressions like '[...]' match a single charcter from a set of charcters.
//example: match vowels in a string
const regex = /[aeiou]/gi;

### Character Classes

### The OR Operator

### Flags

### Character Escapes

## Author

A short section about the author with a link to the author's GitHub profile (replace with your information and a link to your profile)
