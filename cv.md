# [rsschool-cv](https://AliakseiSafonau.github.io/rsschool-cv/cv "Alexey Safonov")
# Alexey Safonov
## Junior Frontend Developer
***
## Contact information:
 * Phone: +375 (44) 7294661
 * E-mail: pharmaceftssma@gmail.com
 * Telegram: @aliakseiSafonau
 * [LinkedIn](https://www.linkedin.com/in/alexey-safonov-494252236 "Alexey Safonov")
 ## About Me
 I dream of working in the IT,fascinated by the corporate culture,
 teamwork,continuous upward movement and creating the future
 ## Education and courses:
 * Development of web applications in Javascript (IT-Academy)
 ## Code example:
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
## Language:
* English level - A2

