# Regex Tutorial
A REGEX is a regular expression that searches for matching values/patterns within a string. The following REGEX is an example that looks for the string to match the general makeup of a Strong password.

# Summary
(?=^.{6,}$)((?=.*\w)(?=.*[A-Z])(?=.*[a-z])(?=.*[0-9])(?=.*[|!"$%&\/\(\)\?\^\'\\\+\-\*]))^.* This regex tutorial will explore the regex of matching an Strong password.
Each component has a specific responsibility to make sure or verify that the user enters an Strong password in the correct strength with a Minimum length of 6, at least 1 uppercase letter, at least 1 lowercase letter, at least 1 number, at least 1 special character

# Table of Contents
* [Anchors](#Anchors)
* [Quantifiers](#Quantifiers)
* [Character Classes](#Character-Classes)
* [Flags](#Flags)
* [Grouping-and-Capturing](#grouping-and-capturing)
* [Bracket-Expressions](#bracket-expressions)
* [Greedy-and-Lazy-Match](#greedy-and-lazy-match)
* [Boundaries](#boundaries)
* [Look-ahead-and-Look-behind](#look-ahead-and-look-behind)

# Regex Components
## Anchors
The example for a Regex ^ anchor asserts position at start of a line. The dollar $ anchor asserts position at the end of a line

## Quantifiers
The example REGEX inlcudes the following quantifiers: +{}*. In this example its a minimum of 6 characters

## Character Classes+
Use the . operator carefully since often class or negated character class (which we’ll cover next) are faster and more precise.

\d, \w and \s also present their negations with \D, \W and \S respectively.

For example, \D will perform the inverse match with respect to that obtained with \d.
## Flags
N/A

## Grouping and Capturing
N/A
## Bracket Expressions
Bracket expressions are used to specify characters to match, they are enclosed in square brackets[]. This regex has 4 bracket expressions: (?=.*[A-Z])(?=.*[a-z])(?=.*[0-9])(?=.*[|!"$%&\/\(\)\?\^\'\\\+\-\*])).

An example of bracket expressions: in the expression *[A-Z], it matches any character in the brackets capitalized A_Z.

## Greedy and Lazy Match
N/A in this regex

## Boundaries
\b represents an anchor like caret matching positions where one side is a word character (like \w) and the other side is not a word character 

## Look-ahead and Look-behind
Lookahead  in this regex would be (?=.*[a-z])


## Author

https://github.com/cburnside1385