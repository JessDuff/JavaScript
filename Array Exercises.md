### Calculate Daily Pay

``` 
function dailyPay(){
    var dogWalks = [4, 5, 2, 2, 6, 1, 3];
    for(var i = 0; i < dogWalks.length; i++){
        console.log("Trisha earned $" + (dogWalks[i] * 22) + " today!");
    }
}
```

![Daily Pay](images/ss_js17.png)

### YELLING

```
function yelling(sentence){
    console.log(sentence.toUpperCase());
}
```
![Yelling](images/ss_js18.png)

### Calculate Total Pay

```
function totalPay(){
    var dogWalks = [4, 5, 2, 2, 6, 1, 3];
    var total = 0;
    for(var i = 0; i < dogWalks.length; i++){
        total = total + (dogWalks[i] * 22);
    }
    return total;
}
```
![Total Pay](images/ss_js19.png)

### Best Client

```
function bestClient(){
    var hourlyPay = [22, 17, 29, 16, 18];
    var bestPay = 0;
     for(var i = 0; i < hourlyPay.length; i++){
         if(hourlyPay[i] > bestPay){
             bestPay = hourlyPay[i];
         }
     }
    return bestPay;
}
```
![Best Client](images/ss_js20.png)



