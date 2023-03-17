# Christina Kushnyarevich

### Contacts

* **Location**: Minsk, Belarus
* **Phone**: +375 44 575-40-66
* **Email**: <christina.kushnyarevich@gmail.com>
* **GitHub**: [Nimvel](https://github.com/Nimvel)

<!-- Краткая информация о себе (ваша цель и приоритеты, подчеркните свои сильные стороны, расскажите о своём опыте работы, если опыта работы нет, расскажите о своём стремлении учиться и узнавать новое)
-->

### Skills

* HTML
* CSS/SASS
* JavaScript (Basic)
* React (Basic)
* Redux (Basic)
* Git

### Code Example

```
function brightest(colors){
  let arr = []
  
  for (let i = 0; i < colors.length; i++) {
    let R = parseInt(colors[i].slice(1, 3), 16)
    let G = parseInt(colors[i].slice(3, 5), 16)
    let B = parseInt(colors[i].slice(5, 7), 16)
    arr.push(Math.max(R, G, B))
  }
  
  let sortArr = [...arr]
  sortArr = sortArr.sort((a, b) => b - a)
  
  for (let i = 0; i < arr.length; i++) {
    if (sortArr[0] === arr[i]) {
      return colors[i]
    }
  }
}
```

### Education

Сollege: 
* Minsk State College of Electronics, computer's operator

University: 
* Belarusian State Technical University, information technology software (only 1 course)
* Minsk State Linguistic University, Chinese-English translator (only 2 course)

Courses:
* [FreeCodeCamp](https://www.freecodecamp.org/)

### English

A2 (I started studying the language at the university and I continue my classes on the Duolingo app)