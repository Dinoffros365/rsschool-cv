# __Jaroslav Halyuta (Junior Frontend Developer)__

## __Contact information:__
* **E-mail:** halutaa17@gmail.com
* **GitHub** [Dinoffros365](https://github.com/Dinoffros365)
  
## About me:
I am 20 years old, I learn in KAI. I learn Frontend DEV 2 years. I complete some course about HTML/CSS. I hope will learn REACT Framework.
- **My strengths:**
    - Quick learn
    - Stay focus long time
    - Stress-resistant
## Skills
* HTML
* CSS
* Core Js
* Git/GitHub
* Figma
## Code examples:
**Angle Between Clock Hands task on CODEWARS:** * Given a Date or hours and minutes, return the angle between the two hands of a 12-hour analog clock in radians. *
```
function handAngle(date) {
    let hours = date.getHours();
    let min = date.getMinutes();

    if (hours >= 12) hours -= 12;


    let angleMin = min * 6;
    let angleHours = hours * 30 + (.5 * min);

    if (angleHours === angleMin) {
        return 0.0;
    } else if (Math.abs(angleHours - angleMin) > 180) {
        return (Math.abs(360 - Math.abs(angleMin - angleHours)) * (Math.PI / 180));
    } else {
        return (Math.abs(angleMin - angleHours) * (Math.PI / 180));
    }
}
```
## Courses:
* HTML and CSS Tutorials on the skillbox
* JavaScript Manual on [learnjavascript.ru](https://learn.javascript.ru/)
* RS Schools Course «JavaScript/Front-end. Stage 0» (myself)
## Languages: 
* Russian - Native
* English - Intermediate
