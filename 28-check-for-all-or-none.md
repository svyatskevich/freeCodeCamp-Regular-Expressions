# Regular Expressions: Check for All or None
Change the regex favRegex to match both the American English (favorite) and the British English (favourite) version of the word.
# Solution:
```javascript
let favWord = "favorite";
let favRegex = /favou?rite/; // Change this line
let result = favRegex.test(favWord);
console.log(result);
```