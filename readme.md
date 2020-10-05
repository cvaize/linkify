# Function that converts links in text to html links
###Example:
```javascript
// FROM: 
// Какой хороший день https://medium.com/keep-network-korea-привет-ё. Лучший день
// TO:
// Какой хороший день <a href="https://medium.com/keep-network-korea-%D0%BF%D1%80%D0%B8%D0%B2%D0%B5%D1%82-%D1%91" 
// target="_blank">https://medium.com/keep-network-korea-привет-ё</a>. Лучший день
import linkify from 'linkify';

console.log(linkify('Какой хороший день https://medium.com/keep-network-korea-привет-ё. Лучший день'));
```
