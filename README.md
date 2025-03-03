# Вербовская Елизавета
## FRONTEND-разработчик
![Моя фотография](/img/kot.jpg)

## Контактная информация
- **Email**: lizbetverb@gmail.com
- **Телефон**: +123 456 7890
- **GitHub**: [github.com//LisVerb](https://github.com/LisVerb)

## О себе
  Я  — начинающий разработчик с тягой к программированию и созданию привлекательных интерфейсов.
  Являюсь ответственным, усидчивым и дружелюбным человеком, умею работать в команде. Люблю изучать что-то новое, а также имею аналитический склад ума.
  
## Навыки

- HTML5, CSS3
- JavaScript
- TypeScript
- React, Redux
- Sass, Bootstrap
- RestAPI
- Adaptive layout

## Пример кода
```
// Функция для перевода строки в нижний регистр
function toLowerCase(str) {
    let lowerStr = '';

    // Проходим по каждому символу строки
    for (let i = 0; i < str.length; i++) {
        let char = str[i];

        // Если символ в верхнем регистре, приводим его к нижнему
        if (char >= 'A' && char <= 'Z') {
            lowerStr += String.fromCharCode(char.charCodeAt(0) + 32);
        } else {
            lowerStr += char;
        }
    }

    return lowerStr;
}

let inputStr = "Hello World!";
console.log("Исходная строка:", inputStr);
console.log("Строка в нижнем регистре:", toLowerCase(inputStr));
```
