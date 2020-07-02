### Invoke a Function:

* Sum

  ![Sum](images/ss_js4.png)
  
* Equations 

  ![Equations](images/ss_js5.png)

* Random 

  ![Random](images/ss_js6.png)

### Try it out

  ![SimpleMath](images/ss_js7.png)

La funcion no tiene retorno.

### You Do

* Say Something 

![Say Something](images/ss_js8.png)

* Show Favorites 

![Show Favorites](images/ss_js9.png)

* Calculate Age 

![Calculate Age](images/ss_js10.png)

## Exercises: Functions

The Fortune Teller

```
function tellFortune(children, partner, location, job){
  console.log("You will be a " + job + " in " + location + " and married to " + partner + " with " + children + " kids.")
}
```
![The Fortune Teller](images/fortune_teller.png)

The Puppy Age Calculator

```
function calculateDogAge(puppyAge){
  var dogYears = puppyAge * 7;
  console.log("Your doggie is " + dogYears + " years old in dog years!")
}
```
![The Puppy Age Calculator](images/puppy_age.png)

The Lifetime Supply Calculator

```
function calculateSupply(age, amountDay){
  var maxAge = 90;
  var amount = (maxAge - age) * 365 * amountDay;
  console.log("You will need " + amount + " to last you until the ripe old age of " + maxAge);
}
```
![The Lifetime Supply Calculator](images/lifetime_supply.png)

The Geometrizer

```
function calcCircumference(radius){
  circumference = 2 * Math.PI * radius;
  console.log("The circumference is " + circumference);
}

function calcArea(radius){
  area = Math.PI * Math.pow(radius, 2);
  console.log("The area is " + area);
}
```
![The Geometrizer](images/geometrizer.png)

The Temperature Converter

```
function celsiusToFahrenheit(celsius){
  var f = (celsius / 5) * 9 + 32;
  console.log(celsius + "°C is " + f + "°F");
}
function fahrenheitToCelsius(fahrenheit){
  var c = (fahrenheit - 32) * 5 / 9;
  console.log(fahrenheit + "°F is " + c + "°C");
}
```
![The Temperature Converter](images/temperature_converter.png)
