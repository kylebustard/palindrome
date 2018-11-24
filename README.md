# Phrase object (with palindrome detector)

The module can be used as follows:

```
$ npm install --global kylebustard-palindrome
$ vim test.js
let Phrase = require("kylebustard-palindrome");
let napoleonsLament = new Phrase("Able was I, ere I saw Elba.");
console.log(napoleonsLament.palindrome());
$ node test.js
true
```
