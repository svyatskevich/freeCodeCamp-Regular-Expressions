# Regular Expressions: Match Letters of the Alphabet
Match all the letters in the string quoteSample.

Note: Be sure to match both uppercase and lowercase letters.
# Solution:
```javascript
let quoteSample = "The quick brown fox jumps over the lazy dog.";
let alphabetRegex = /[a-z]/gi; // Change this line
let result = quoteSample.match(alphabetRegex); // Change this line
```