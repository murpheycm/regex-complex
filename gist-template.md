# Regex for Phone Number Validation (North America)

A Github gist tutorial that explains how the regular expression, or regex, for phone number validation functions by breaking down each part of the expression and describing what it does. 

## Summary

This tutorial will focus on the following North American phone number validation regex:
> 
> Regex: /^\d{3}-\d{3}-\d{4}$/ <br>
> Example: ###-###-#### <br>

The tutorial will cover anchors, quantifiers, character escapes, and metacharacters.

This regex is designed to match a specific pattern:

> It must start at the beginning of a line (^).<br>
> It should have exactly three digits, followed by a hyphen (\d{3}-).<br>
> Then, it should have exactly three more digits and another hyphen (\d{3}-).<br>
> Finally, it should end with exactly four digits (\d{4}).<br>
> It must end at the end of a line ($).<br>

## Table of Contents

- [Anchors](#anchors)
- [Quantifiers](#quantifiers)
- [Metacharacters](#metacharacters)
- [Character escapes](#characters)


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




## Author

Mackenzie M. - A UofR Full-Stack Web Development coding bootcamp student. <br>
Github Project Repository - https://github.com/murpheycm/regex-complex
