# Regular Expressions: Match Everything But Letters and Numbers
Use the shorthand character class \W to count the number of non-alphanumeric characters in various quotes and strings.
# Solution:
```javascript
let quoteSample = "The five boxing wizards jump quickly.";
let nonAlphabetRegex = /\W/g; // Change this line
let result = quoteSample.match(nonAlphabetRegex).length;
```