# Regular Expressions: Specify Upper and Lower Number of Matches
Change the regex ohRegex to match the entire phrase Oh no only when it has 3 to 6 letter h's.
# Solution:
```javascript
let ohStr = "Ohhh no";
let ohRegex = /Oh{3,6}.no/; // Change this line
let result = ohRegex.test(ohStr);
```