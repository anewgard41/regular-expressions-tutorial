# Regular Expressions (Regex) Tutorial 

Regular Expressions! What are they? How do they work? Why do they exist? These are all questions that will be answered in this tutorial (hopefully)! Regular expressions are a sequence of characters that define a search pattern. They are used to find and replace patterns in a string or file. They are also used to validate input. Regular expressions are used in many programming languages, command line tools, and text editors. Through the use of literal and meta characters, regular expressions can be used to identify text patterns. 

## Summary

The regular expression I will walk through is an regex used to match an email that follows this general structure: `username@domain.extension`

Here is a snippet of the regex: `/^([a-z0-9_\.-]+)@([\da-z\.-]+)\.([a-z\.]{2,6})$/`

This regex will match an email address that contains letters, numbers, underscores, periods, and hyphens in the name section. It will also match emails that contain a domain name that contains letters, numbers, underscores, periods, and hyphens. The domain proceeds the @ symbol, a *literal character*. The domain name must also end with a dot and an official extension, or top-level domain, such as .com, .edu, .net, etc. The extension must be between 2 and 6 characters long.

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

Anchors are used to match a position within a string. They are used to match a position before, after, or between characters. Anchors are used to match patterns at the beginning and end of a line. The `^` anchor matches the beginning of a string. The `$` anchor matches the end of a string. The `^` anchor is used in the regex to match the beginning of the email address. The `$` anchor is used to match the end of the email address.

### Quantifiers

Quantifiers enable you to specify how many of a character or character class should be matched. In the above string, the `+` quantifier is used to match one or more of the preceding token. The `+` quantifier is used to match one or more of the characters in the username and domain name. The `{2,6}` quantifier is used to match between 2 and 6 characters in the extension.

### Grouping Constructs

Grouping constructs are used to group tokens together and treat them as a single unit. They are created by placing the characters to be grouped inside a set of parentheses. The `()` grouping construct is used to group the username, domain name, and extension together. The same `()` grouping construct is once again used to group the domain name and extension together.

### Bracket Expressions

Bracket expressions are used to match a single character out of a set of characters. They are created by enclosing a set of characters inside a pair of brackets. In the above example, `[a-z0-9_\.-]` is used to match any lowercase letter, number, underscore, period, or hyphen in the username. `[\da-z\.-]` is used to match any digit, lowercase letter, period, or hyphen in the domain name. `[a-z\.]` is used to match any lowercase letter or period in the extension.

### Character Classes

Character classes are used to match a set of characters. They can be used to distinguish between letters and digits. In the above example, `\d` is used to match any digit in the domain name. They can also be created with bracket expressions. In the above example, `[a-z]` is used to match any lowercase letter in the extension.

### The OR Operator

The OR operator is used to match one of two or more expressions. It is created by placing a vertical bar `|` between two or more expressions. There are no OR operators in the above example.

### Flags

Flags are used to perform functions such as global searches `g`, case-insensitive searches `i`, and multiline searches `m`. There are other flags that can be used as well. 

### Character Escapes

Character escapes are used to match a character that has special meaning in regex. They are created by placing a backslash `\` in front of the character. In the above example, `\.` is used to match a period in the username and domain name. `\.` is also used to match a period in the extension.

## Author

Thanks for reading y'all! My name is Anders Newgard and I am a fullstack web developer. I hope you found this tutorial useful! You can find the link to my github below if you wish to contact me or check out some of my other projects. I would love to connect with you! I am open to collaboration in any and all forms. Cheers!

- Github: https://github.com/anewgard41
- Email: anewgard41@gmail.com
