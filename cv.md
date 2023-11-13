# OLGA NEVZOROVA

![photo](./IMG_5554.png)

## JUNIOR FRONTEND DEVELOPER

---

### ABOUT ME

> _I can work in a team, have organizational skills. I'm responsible and interested in the successful completion of any task. I constantly improve my knowledge and skills._

---

### CONTACTS

- tel.: +375(29)3-63-85-54
- mail: neuzorova@gmail.com
- discord: olganevzorova_neuzorovaolg_16380
- loc.: Gomel, Belarus

### SKILLS

- HTML/CSS
- JavaScript
- React
- Firebase
- Material UI
- Git/Github

### EDUCATION

- Belarus State University Of Transport
  - 2010 - 2015 Bachelor’s Degree
    (_Traffic organization_)
  - 2015 - 2016 Master’s Degree
    (_Intelligent technologies in the management of technical systems_)

### EXPERIENCE

- Belarus State University Of Transport
  - 2016 - 2023 Department assistant

### COURSES

- IT Step 2022-2023
  - Frontend developer

### LANGUAGES

- English (A2)
- Russian (native speaker)

### CODEWARS SOLUTION

```JS
  function additionWithoutCarrying(a, b) {
  const arrayA = Array.from(String(a), Number);
  const arrayB = Array.from(String(b), Number);
  let zeroLength = 0;
  let newArrayA;
  let newArrayB;

  if (arrayA.length <= arrayB.length) {
    zeroLength = arrayB.length;
    newArrayA = Array.from(
      String(a).padStart(zeroLength, "0"),
      Number
    ).reverse();
    newArrayB = arrayB.reverse();
  } else if (arrayA.length >= arrayB.length) {
    zeroLength = arrayA.length;
    newArrayB = Array.from(
      String(b).padStart(zeroLength, "0"),
      Number
    ).reverse();
    newArrayA = arrayA.reverse();
  }

  let sum = [];
  for (i = 0; i < zeroLength; i++) {
    let count = Array.from(String(newArrayA[i] + newArrayB[i]));
    if (count[1]) {
      sum.push(count[1]);
    } else {
      sum.push(count[0]);
    }
  }
  return Number(sum.reverse().join(""));
}
```
