# Title (replace with your title)

Introductory paragraph (replace this with your text)

## Summary

Briefly summarize the regex you will be describing and what you will explain. Include a code snippet of the regex. Replace this text with your summary.

## Table of Contents

- [Anchors](#anchors)
- [Quantifiers](#quantifiers)
- [OR Operator](#or-operator)
- [Character Escapes](#character-escapes)
- [Character Classes](#character-classes)
- [Flags](#flags)
- [Grouping and Capturing](#grouping-and-capturing)
- [Bracket Expressions](#bracket-expressions)
- [Greedy and Lazy Match](#greedy-and-lazy-match)
- [Boundaries](#boundaries)
- [Back-references](#back-references)
- [Look-ahead and Look-behind](#look-ahead-and-look-behind)

## Regex Components

<!-- phone: `((\\d{3})(?:\\.|-))?(\\d{3})(?:\\.|-)(\\d{4})` -->

Email: `/^([a-z0-9_\.-]+)@([\da-z\.-]+)\.([a-z\.]{2,6})$/`

<!-- URL: `/^(https?:\/\/)?([\da-z\.-]+)\.([a-z\.]{2,6})([\/\w \.-]*)*\/?$/` -->

### Anchors

`/^ mean start with`
`$/ mean end with`

### Quantifiers

`[a-z] mean a-z any charaters`
`{2,6} mean only can have 2-6 charaters`
`This means that we want to find the preceding string pattern a minimum of 2 times and a maximum of 6 times also match a-z any charaters`
`+ — Matches the pattern one or more times`

### OR Operator

### Character Escapes

`The backslash (\) in a regex escapes a character that otherwise would be interpreted literally. `

### Character Classes

`. — Matches any character except the newline character (\n)`
`\d — Matches any Arabic numeral digit. This class is equivalent to the bracket expression [0-9].`

### Flags

### Grouping and Capturing

`Here used three Enable grouping`
`([a-z0-9_\.-]+)`
`([\da-z\.-]+)`
`([a-z\.]{2,6})`

### Bracket Expressions

`[a-z0-9_\.-] can be a-z or 0-9 also the string can contain an underscore, period or hyphen`

### Greedy and Lazy Match

### Boundaries

### Back-references

### Look-ahead and Look-behind

## Author

A short section about the author with a link to the author's GitHub profile (replace with your information and a link to your profile)
