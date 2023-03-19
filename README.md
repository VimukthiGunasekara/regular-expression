# Regular Expression Tutorial

An email must be matched with (([a-z0-9_/.-]+)@([da-z\.-]+)\.([a-z\.]{2,6})$/ Regex. The concepts behind regular expressions can be difficult to understand, but it is possible to accomplish some pretty incredible things using them. In this article, we will explore a particular example involving matching an email using a regular expression. Once we have identified the components of regular expressions, we will break them down further.

## Summary

Briefly summarize the regex you will be describing and what you will explain. Include a code snippet of the regex. Replace this text with your summary.

## Table of Contents

- [Anchors](#anchors)
- [Quantifiers](#quantifiers)
- [Grouping Constructs](#grouping-constructs)
- [Bracket Expressions](#bracket-expressions)
- [Character Classes](#character-classes)
- [The OR Operator](#the-or-operator)
- [Flags](#flags)
- [Character Escapes](#character-escapes)
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

### The OR Operator
Using an alternative is actually a simple OR, which is represented or declared by a vertical line. For example, you would use cat|dog|bird to search for three different things, including cats, dogs, and birds. The result would be that you would request that all three of those items be searched for in groups at the same time, as well as individually.

<a href="https://javascript.info/regexp-alternation">More</a>

### Flags
As far as JavaScript is concerned, there are only six flags that are compatible with JavaScript and retro regular expressions; these are "I," which searches for casein sensitive characters. A G flag is used to locate anything outside of a specified request, a M flag makes use of a dot to match, and a character U flag allows pairs to be processed correctly. The sticky flag is used to locate a particular position.

<a href="https://javascript.info/regexp-introduction">More</a>

### Character Escapes

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

