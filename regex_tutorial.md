# REGEX TUTORIAL: HTML TAGS

Regex is a way of searching through text patterns in code. With a vast range of uses such matching emails, HEX values, URL's, and even the particular foucus of this article HTML tags

## Summary

The intention of this particluar article is to display the use of regex for html tags.and walk the reader through amethod in which they can find html tags throughtout their own code. Regex is used when searching "ctrl+f" or can be used to validate information.

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
/<(\w+)(\d*)>|</(.*) >/

Regex componets consist of single characters, wild card, bracket expressions, control characters, and escsape sets. Regex components can either be metacharacters(have a special meaning) or have regular charcters for there literal meaning. For example in regex "\d"(escape set) is a metacharacter which means any character between 0-9. While "."(wild card) stands for any single character except "\n"(a new line) at all but "\." is the literal period. Now for the above regex formula it is to search for any html tags using literal and metacharacteres. Being match the literal "<" with any letter character one or more with any digit 0-9 following it and ends with the literal ">" character. then the OR pipeline withe the literal "<" and a backslash accomapanied with any character 0 or more ending with a ">". 


### Anchors

Anchors are unigue characters used to define the beginning or the end of a string. the character used to for the beginning of a string "^" while its counter part is "$" in other words is for the end of a string.

### Quantifiers

There are serveral different quantifiers in regex which are represented with these characters: *,+,?, and {}. The * is a quantifer representing 0 or more. While + is a quantifier the represents 1 or more. Now as for the ? is a quantifier that represents 0 or 1. Regex is inheritly greedy to search for and occurence the mininal amount of times ? will come in handy.

### Grouping Constructs

Grouping constructs are used within parentheses to capture subexpressions. To match the text in your code to particluar patteren asked for within the parentheses.

### Bracket Expressions

Represent a character set that is enclosed with sqaure bracketes. It normally matches the target string with any single character from the list that is within the bracket. For example "[or]" would match all the instances in which "or" is together on this page weather it is apart of a word or is its own word all together.  

### Character Classes

### The OR Operator

### Flags

### Character Escapes

## Author

A short section about the author with a link to the author's GitHub profile (replace with your information and a link to your profile)
