
---
# Anna
## Contacts
* **Location:** Russia
* **Phone:** +7 123 456 78 90
* **Email:** anna123@gmail.com
* **GitHub:** AnnStarrySky
## About Me
I have been engaged in sales and customer service for a long time. During my maternity leave, I decided to change my profession. I can learn on my own. I constantly develop my professional skills. I have teamwork skills.
## Skills
* HTML
* CSS
* Java Script
* Figma
* GitHub
## Code Examples
Write a function that takes in a string of one or more words,
and returns the same string, but with all words that have five or more letters reversed (Just like the name of this Kata). Strings passed in will consist of only letters and spaces.
Spaces will be included only when more than one word is present.
```javascript
function spinWords(string){
    let words = string.split(' ');
    let result = words.map(word => {
        if (word.length >= 5) {
            return word.split('').reverse().join('');
        }
        return word;
    });
    return result.join(' ');
};
```
## Education
* **University:**
  * I have a higher education.
  * I have a degree in engineering and economics.
* **Courses:**
  * SkillBox: Front-end developer
  * Udemy: JavaScript + React (in progress)
## Languages
  * **Russian:** native speaker
  * **English:** А1
