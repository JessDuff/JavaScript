### Object Literals

![Object Literals](images/ss_js23.png)

### Dot Notation

![Dot Notation](images/ss_js24.png)

### Reassigning Properties

![Reassigning Properties](images/ss_js25.png)

### Nested Objects

![Nested Objects](images/ss_js26.png)

### Objects as Arguments

```
var melissa = {
  name: "Melissa",
  program: "Front End",
  module: 1,
  alum: false
}
var zack = {
  name: "Zack",
  program: "JS",
  module: 2,
  alum: true
}
var joe = {
  name: "Joe",
  program: "C++",
  module: 1,
  alum: false
}
function message(student) {
  console.log(student.name + " is one of our awesome " + student.program + " students, currently in module " + student.module + "!");
}
```

![Objects as Arguments](images/ss_js27.png)

### Challenge

```
var student = {
  name: "Allie",
  program: "Front End",
  module: 1,
  alum: false,
  projects: ["Dog Party", "Number Guesser", "Check Yo Self"]
}
function projects() {
  var last = " and " + student.projects.slice(student.projects.length - 1);
  var p = student.projects.slice(0, student.projects.length - 1);
  console.log(student.name + " is an awesome " + student.program + " student! They have built the following projects: " + p + last);
}
```
![Challenge](images/ss_js28.png)
