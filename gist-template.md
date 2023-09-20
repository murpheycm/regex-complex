# Regex for Phone Number Validation (North America)

A GIST tutorial that explains how the regular expression, or regex, for phone number validation functions by breaking down each part of the expression and describing what it does. 

## Summary

This tutorial will focus on the following North American phone number validation regex:
>
> /^\d{3}-\d{3}-\d{4}$/
>
The tutorial will cover anchors, quantifiers, character escapes, metacharacters, boundaries, and escape sequences.

## Table of Contents

- [Anchors](#anchors)
- [Quantifiers](#quantifiers)
- [Metacharacters](#metacharacters)
- [Character escapes](#characters)
- [Boundaries](#boundaries)

## Regex Components

### Anchors
Regex: /^\d{3}-\d{3}-\d{4}$/
> `^` at the beginning and `$` at the end are anchors.<br>
> `^` asserts the start of a line.<br>
`$` asserts the end of a line.<br>
Together, `^` and `$` ensure that the entire string matches the pattern, not just a portion of it.

### Quantifiers
Regex: /^\d{3}-\d{3}-\d{4}$/
> `\d{3}` matches exactly three digits. <br>
> `\d{4}` matches exactly four digits. <br>
> These quantifiers specify the number of times a character or group should be repeated.

### Metacharacters
Regex: /^\d{3}-\d{3}-\d{4}$/
> `-` is a metacharacter. <br>
> `-` matches the hyphen character literally. <br>
In this regex, hyphens are used as separators between groups of digits.

### Characters: Escapes
Regex: /^\d{3}-\d{3}-\d{4}$/
> `\d` is a character escape. <br>
> `\d` matches any digit (0-9). <br>
The `\d` escape simplifies the pattern by matching any digit character.

### Boundaries


## Author

Mackenzie M. - A UofR Full-Stack Web Development coding bootcamp student. <br>
Github Project Repository - https://github.com/murpheycm/regex-complex
