<!-- # Title (replace with your title)

Introductory paragraph (replace this with your text)

## Summary

Briefly summarize the regex you will be describing and what you will explain. Include a code snippet of the regex. Replace this text with your summary. -->


# Tutorial: Regular Expressions: Exploring Regex

## Introduction:
Regular expressions (regex) are tools for pattern matching and text manipulation. 

As a web dev student, understanding regex is needed for tasks like data validation & extraction. 

## Summary:

Regular expressions AKA "regex" are tools used for tasks like data extraction and validation. They provide a specific way to search, extract and manipulate strings of characters. 

In this tutorial, I will break down a specific regex pattern and explain each part to help users understand how regex really works. 

## Table of Contents

The regex patterns we'll be learning in this tutorial are:
- [Anchors](#anchors)
- [Quantifiers](#quantifiers)
- [Grouping Constructs](#grouping-constructs)
- [Bracket Expressions](#bracket-expressions)
- [Character Classes](#character-classes)
- [The OR Operator](#the-or-operator)
- [Flags](#flags)
- [Character Escapes](#character-escapes)

<!-- ## Regex Components -->

<!-- ### Anchors -->

<!-- ### Quantifiers -->

<!-- ### Grouping Constructs -->

<!-- ### Bracket Expressions -->

<!-- ### Character Classes -->

## Regex Components

### Anchors 
Anchors are regex constructs used to assert positions in the input string. The two commonly used anchors are:

- The caret (`^`) asserts the start of the string. It ensures that the matching pattern starts at the beginning of the input.

- The dollar sign (`$`) asserts the end of the string. It ensures that the matching pattern ends at the end of the input.

### Quantifiers 
Quantifiers specify how many times a particular element should occur in the input. They control the repetition of characters or groups. 

Here are some commonly used quantifiers:
- `*` matches zero or more occurrences of the preceding element.
- `+` matches one or more occurrences of the preceding element.
- `?` matches zero or one occurrence of the preceding element.
- `{n}` matches exactly n occurrences of the preceding element.
- `{n,}` matches at least n occurrences of the preceding element.
- `{n,m}` matches between n and m occurrences of the preceding element.

### Grouping Constructs 
Grouping constructs allow you to treat multiple elements as a single unit. They are denoted by parentheses `()`.

 Here are some use cases of grouping constructs:
- `(abc)` matches the sequence "abc" exactly.
- `(a|b)` matches either "a" or "b".
- `(?:abc)` is a non-capturing group. It allows grouping without creating a backreference.

### Bracket Expressions 
Bracket expressions, also known as character classes, allow you to define a set of characters to match. They are denoted by square brackets `[]`.

 Here are some examples:
- `[aeiou]` matches any vowel character.
- `[^0-9]` matches any character that is not a digit.
- `[A-Za-z]` matches any uppercase or lowercase alphabetical character.

### Character Classes 
Character classes are predefined sets of characters that represent common patterns. They are denoted by backslash `\` followed by a character.

 Here are some commonly used character classes:
- `\d` matches any digit character.
- `\w` matches any word character (alphanumeric and underscore).
- `\s` matches any whitespace character.
- `\D` matches any non-digit character.
- `\W` matches any non-word character.
- `\S` matches any non-whitespace character.


### The OR Operator

### Flags

### Character Escapes

## Author

A short section about the author with a link to the author's GitHub profile (replace with your information and a link to your profile)
