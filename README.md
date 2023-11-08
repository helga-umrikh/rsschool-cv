# Olga Umrikhina
### Contacts:

**phone:**  *[+5 555-555-55-55](tel:1111111)*  
**email:**  *[ hello@hello.com](mailto:zetaumr@gmail.com)*  
**LinkedIn:**  *[olga-umrikhina](www.linkedin.com/in/olga-umrikhina)*  
**GitHub:**   *[helga-umrikh](https://github.com/helga-umrikh)*

## Summary
Hello! My name is Olga Umrikhina and I am excited to apply for the internship opportunity at your software company. With a background in music from graduating from a conservatory, I decided to pursue my passion for programming and recently completed a course in frontend development School. I have the flexibility to either move to another country or work remotely, depending on the requirements and opportunities that arise. I am also driven by a passion for learning, constantly seeking to expand my knowledge and skills. I immerse myself in books like "Grokking Algorithms: An Illustrated Guide for Programmers and Other Curious People" by Aditya Y. Bhargava, and I also actively engage with online courses and YouTube channels to deepen my understanding of JavaScript.

## Skills
``HTML``   ``CSS``  ``JavaScript`` ``GIT`` ``SASS`` ``React`` ``Redux``

## Code Examples

```javascript
function order(words){
  let str = words.split(' ');
  let textMap = new Map();
  
  str.forEach((e) => {
    let number = e.match(/\d+/g);
    textMap.set(number, e);
  })
  
  let sortedArr= Array.from(textMap.entries()).sort((a, b) => a[0] - b[0]);
  let result = sortedArr.map(e => e[1]).join(' ');
  
  return result;
}
```