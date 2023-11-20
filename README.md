# Regular Expressions (Regex) Tutorial 

Regular Expressions! What are they? How do they work? Why do they exist? These are all questions that will be answered in this tutorial. Regular expressions are a sequence of characters that define a search pattern. They are used to find and replace patterns in a string or file. They are also used to validate input. Regular expressions are used in many programming languages, command line tools, and text editors. Through the use of literal and meta characters, regular expressions can be used to identify text patterns. 

## Summary

The regular expression I will walk through is an regex used to match an email that follows this general structure: `name@domain.com`

Here is a snippet of the regex: `/^([a-z0-9_\.-]+)@([\da-z\.-]+)\.([a-z\.]{2,6})$/`

This regex will match an email address that contains letters, numbers, underscores, periods, and hyphens in the name section. It will also match emails that contain a domain name that contains letters, numbers, underscores, periods, and hyphens. The domain proceeds the @ symbol, a *literal character*. The domain name must also end with a dot a and an official extension, such as .com, .edu, .net, etc. The extension must be between 2 and 6 characters long.

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

### Quantifiers

### Grouping Constructs

### Bracket Expressions

### Character Classes

### The OR Operator

### Flags

### Character Escapes

## Author

A short section about the author with a link to the author's GitHub profile (replace with your information and a link to your profile)
