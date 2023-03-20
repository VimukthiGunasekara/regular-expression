# Regular Expression Tutorial

An email must be matched with (([a-z0-9_/.-]+)@([da-z\.-]+)\.([a-z\.]{2,6})$/ Regex. The concepts behind regular expressions can be difficult to understand, but it is possible to accomplish some pretty incredible things using them. In this article, we will explore a particular example involving matching an email using a regular expression. Once we have identified the components of regular expressions, we will break them down further.

## Summary

Basically, a regular expression is a pattern describing a certain amount of text. Their name comes from the mathematical theory on which they are based. But we will not dig into that. You will usually find the name abbreviated to "regex" or "regexp". This tutorial uses "regex", because it is easy to pronounce the plural "regexes". On this website, regular expressions are shaded gray as regex.

This first example is actually a perfectly valid regex. It is the most basic pattern, simply matching the literal text regex. A “match” is the piece of text, or sequence of bytes or characters that pattern was found to correspond to by the regex processing software. Matches are highlighted in blue on this site.

``` 
\b[A-Z0-9._%+-]+@[A-Z0-9.-]+\.[A-Z]{2,}\b
``` 
is a more complex pattern. It describes a series of letters, digits, dots, underscores, percentage signs and hyphens, followed by an at sign, followed by another series of letters, digits and hyphens, finally followed by a single dot and two or more letters. In other words: this pattern describes an email address. This also shows the syntax highlighting applied to regular expressions on this site. Word boundaries and quantifiers are blue, character classes are orange, and escaped literals are gray. You’ll see additional colors like green for grouping and purple for meta tokens later in the tutorial.

With the above regular expression pattern, you can search through a text file to find email addresses, or verify if a given string looks like an email address. This tutorial uses the term “string” to indicate the text that the regular expression is applied to. This website highlights them in green. The term “string” or “character string” is used by programmers to indicate a sequence of characters. In practice, you can use regular expressions with whatever data you can access using the application or programming language you are working with.

## Table of Contents

- [Anchors](#anchors)
- [Quantifiers](#quantifiers)
- [Grouping Constructs](#grouping-constructs)
- [Bracket Expressions](#bracket-expressions)
- [Character Classes](#character-classes)
- [The OR Operator](#the-or-operator)
- [Flags](#flags)
- [References](#references)

## Regex Components

### Anchors
It is possible to use anchors to describe word boundaries or lack thereof. Anchors include symbols like a caret and a dollar sign at the end of the string. Anchors are the point at which a string begins or ends. An anchor is an example of an anchor, such as a carrot and a $. Anchors are a way of telling you where you are, so basically, is that the beginning or the end? As for /A, this is the beginning of a string. If we talk about regex, it is important to note that it varies from language to language when it comes to regex. While some characters are the same across multiple languages and have the same meaning, that isn't the case for all of them, so it is important to find good references. It is important to keep an eye out for symbols or characters in the documentation that are labelled with notes that indicate that they are the same for all engines except JavaScript, for Ruby, or all of these are the same based on the language. Regular expressions have the following quantifiers: *, +, ?, {3}, {4,7}, {5,}.

### Quantifiers
Quantifiers in regex include ?,*, +, and items within curly braces or brackets. The purpose of quantifiers is to determine how often or how many of something happens. Based on my research, it has been determined that quantifiers can also be eagerly and reluctantly possessive depending on their placement. Hovering over those different parts of the expression will provide you with an explanation of what each letter or character does in order to create a particular expression. At the bottom of the page, they also provide a helpful cheat sheet. In terms of quantifiers, if you look at W3 schools, almost or all of the descriptions start with “matches any string with” or “matches any string that.” In each of the examples they provide, they provide more details, such as, matching any string with and ends at the end of it, or for the example of n $, it is the same thing. As another example, if you had a? Equals n, it would say that it matches any string that follows a specific string, which would be if you had a? Equals n. Quantifiers specify what is required in order to match the OR operator

### Grouping Constructs
Capturing and Grouping An easy example of capturing and grouping would be to say that you have a cat. As you consider grouping and capturing, let us use the sixth sample of a cat with his parentheses, then a regular expression will either convert the screw cat into a single character or view it as a single character, resulting in C A T being viewed as a single character.

### Bracket Expressions
The article at the bottom of this section discusses bracket expressions in-depth, as well as explains the differences between square brackets, curly braces, and parentheses. When brackets are present, the viewer, user, or program is instructed to determine if any individual characters are similar within the brackets. With the curly braces, they do something a little bit different their job is to say or define a specific number of things to match. So, for example, you could say I want to match exactly two times this one example. In terms of parentheses, these are remembered matches. They are useful whenever you wish to do something with a particular part of a match. They can be used to reference a remembered match or a remembered portion of a match which would be useful to discuss at a later date.

<a href="https://javascript.plainenglish.io/regular-expressions-brackets-f2d6f69ffe13">More</a>

### Character Classes
The character class a-z or A-Z is a good example of a character class - when this is used in a regular expression, it does not just mean finding a timeframe, but rather it means searching through everything in the alphabet. So anything between A-Z could be any one of those characters, so you could use this A-Z or you could also consider numbers. There is also the possibility of using numbers.

Syntax for the same would be:,
- ** \d ** - matches a single character that is a ** digit ** between 0 to 9
- ** \w ** - matches a ** word ** character [A-Za-z0-9_]
- ** \s ** - matches a ** whitespace ** character
- ** \D ** - matches a ** NON-digit ** character In the case of macthing an email: /^([a-z0-9_\.-]+)@([\da-z\.-]+)\.([a-z\.]{2,6})$/ -- \d would represents a single digit ranging from the numerical values 0 to 9 after the @ sign in email address. this string will only match a single digit such as "2", but not "22" or "12".

### The OR Operator
Using an alternative is actually a simple OR, which is represented or declared by a vertical line. For example, you would use cat|dog|bird to search for three different things, including cats, dogs, and birds. The result would be that you would request that all three of those items be searched for in groups at the same time, as well as individually.

<a href="https://javascript.info/regexp-alternation">More</a>

### Flags
As far as JavaScript is concerned, there are only six flags that are compatible with JavaScript and retro regular expressions; these are "I," which searches for casein sensitive characters. A G flag is used to locate anything outside of a specified request, a M flag makes use of a dot to match, and a character U flag allows pairs to be processed correctly. The sticky flag is used to locate a particular position.

<a href="https://javascript.info/regexp-introduction">More</a>

### References

https://javascript.info/regexp-backreferences  </br> 
https://javascript.info/regexp-greedy-and-lazy  </br> 
http://www.rexegg.com/regex-anchors.html </br> 
https://cs.lmu.edu/~ray/notes/regex/  </br>
https://www.regular-expressions.info/lookaround.html </br>
https://www.javascripttutorial.net/regular-expression-word-boundaries/

## 🌎 Author
<img align="left" width="150" height="150" src="Icon.gif">
Sharing updates on

<a href="https://www.linkedin.com/in/vimukthi-gunasekara/">LinkedIn</a> 💼 </br>
<a href="https://github.com/VimukthiGunasekara">GitHub</a> 💻 </br>
<a href="https://twitter.com/Vimu_Gunasekara">Twitter</a> 🐦 </br>
<a href="https://www.instagram.com/vimukthi_gunasekaraa/">Instagram</a> 📷 </br>
<a href="https://vimukthigunasekara.github.io/react-portfolio/">Portfolio</a> 🧔 </br>

