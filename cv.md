## [rsschool-cv](https://AliakseiSafonau.github.io/rsschool-cv/ "Alexey Safonov")
# Alexey Safonov
### Junior Frontend Developer
 I approach every aspect of my work with professional responsibility and a high degree of
 punctuality. My resilience and decisiveness allow me to remain focused and efficient even in the
 most stressful situations. Courtesy and communicability enable me to establish contacts at all levels
 of interaction successfully. Attention to detail and a strong sense of duty ensure the high quality of
 task execution.
***
### Contact information:
 * Phone: +375 (44) 7294661
 * E-mail: pharmaceftssma@gmail.com
 * Telegram: @aliakseiSafonau
 * [LinkedIn](https://www.linkedin.com/in/aliaksei-safonau-771b61301/ "Alexey Safonov")
### Professional skills
 * Programming languages
  JS (ECMAScript 5-9), TypeScript, PHP, Python
 * HTML/CSS coding
  HTML5, CSS3, Sass/Scss
 * Frameworks/ Libraries
  React, Vue, Django, FastAPI
 * State managers
  Redux, Vuex
 * Backend experience
  Node.js, Python
 * Version control system
  Git, GitHub, GitLab
 * Docker
 * IDE
  Visual Studio Code, WebStorm, PyCharm
 * Teamwork
### Education and courses:
 * Development of web applications in Javascript (IT-Academy)
 End date: feb 2022
 Specialty: Frontend Developer
### Code example:
```javascript
class Calculations {

    intermediate(data) {

        return data.reduce((total, amount) => {
            for (let keyAmount in amount) {
                if (total[keyAmount] && typeof amount[keyAmount] === 'object') {
                    for (let key in amount[keyAmount]) {
                        if (total[keyAmount][key]) {
                            total[keyAmount][key] = String(Number(total[keyAmount][key]) + Number(amount[keyAmount][key]))
                        } else {
                            total[keyAmount][key] = amount[keyAmount][key]
                        }
                    }
                } else total[keyAmount] = amount[keyAmount];
            }
            return total;
        }, {})
    }
}
```
### Language:
* English level - A2
* French level - A2

