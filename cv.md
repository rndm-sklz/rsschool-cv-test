# Andrey Gerasimov
***
## Junior frontend developer
***
### Contact information

* *Gender*: Male
* *City*: Rostov-on-Don
* *E-mail*: gerasimov-am@yandex.ru
* *Telegram*: [@Gerasimov_Andrew](https://telegram.me/Gerasimov_Andrew)

***
### About me

Hello, my name is Andrey, i'm frontend trainee from Rostov-on-Don.
At the moment I am independently learning JS, CSS and HTML.
I look forward to developing my skills from this course.

***
### My skills

* HTML 5
* CSS 3
* JavaScript (basic)
* Git (basic)

***

### Code example


```js
let container = document.createElement("div", { id: "container" });
document.body.appendChild(container);

function chessBoard(n, m) {
  let table = document.createElement("table");
  container.appendChild(table);
  for (let i = 0; i < n; i++) {
    let tr = document.createElement("tr");
    table.appendChild(tr);

    for (let j = 0; j < m; j++) {
      if (i % 2 === 0) {
        let td = document.createElement("td");
        j % 2 === 0
          ? td.classList.add("cell--dark")
          : td.classList.add("cell--light");
        tr.appendChild(td);
      } else {
        let td = document.createElement("td");
        j % 2 !== 0
          ? td.classList.add("cell--dark")
          : td.classList.add("cell--light");
        tr.appendChild(td);
      }
    }
  }
}

chessBoard(6, 6);
```

[Link to this example](https://codepen.io/rndm-sklz/pen/OJxWapw)

***

### Work experience

As frontend developer - none :)

### Education

* [HTML Academy](https://htmlacademy.ru/profile/oldschool)
* [Codewars](https://www.codewars.com/users/rndm-sklz)
* [Codepen](https://codepen.io/rndm-sklz)

### Languages

* English: Currently at ___A1___ level (Checked at [efset](https://www.efset.org/) test)
* Russian: Native