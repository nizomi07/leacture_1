![alt text](image.png)

# ***JS or with other words JavaScript***
___
### The creater of the first version of JS is Brendan Eich
___

## The first name of JS was __Mocha__ then change it to the LS ( Live Script )
## Finally it change to JS (Java Script)
> * MOCHA
>> * LS (Live Script)
<br><br>
***Finally***
>>> * JS (Java Script)
>>>

<br><br>
___

# ES or EcmaScript is the version or standart of JS
## In Javascript there is two types of intializing variables, var and let. You can use both of   them.
## However, there are some differences between them.
## In programming, a variable is a container (storage area) to hold data.
## If you are sure that the value of a variable won't change throughout the program, it's 
## recommended to use const .

# The DataType divides into two groups
```
Objects 
> Number
> String
> Boolean
> Undefined
> Null
> Symbol
> BigInt

Primitives
> Objects
    > Object Literal
    > Arrays
    > Functions
    > Many more ...
```
## Variable names must start with either a letter, an underscore _, or the dollar sign $
+ let `text` = "text";
+ let `_text` = "text";
+ let `$text` = "text";
<br>
# ___***Operators IN JavaScript***___
> ***Names*** ==========> ***Operators***
>> `Arithmetic` ==> `+, -, *, /`
>> <br>
>> `Comparison` ==> `==, ===, >=, <=, !=, !===`
>> <br>
>> `Logical` ==> `||, &&, !0`
>> <br>
>> `Type Conversions` ==> `Number("3.14)`
>> <br>
>> `Assignment` ==> `=, +=, -=, *=, /=, ^=, %=`
>> <br>

# ***CONDITION*** in __JS__
## ___First_One___
+ __*CONDITION*__ __if/else__ __*STATEMENT*__

```python
let number = 0;
if(number > 0) {
    // code here
}
else if(number == 0) {
    // code here
}
else {
    // code here
}

// code after if

```
+ __*CONDITION*__ __Ternary operator__

```python
    return or console.log() //code here ? : "true" and otehr ....
    condition ? true : false

```

+ __*CONDITION*__ __Switch__ __*STATEMENT*__

```python
    let expr = "Apple";

    switch (expr) {
        case "Orabge":
            console.log("Orange are $0.59 a pound.");
        case "Pear":
            console.log("Pear are $2 and 5 pounds.");
        default:
            console.log("Sorry, we are out of ${expr}.");
    }
```
<br><br>
___
# ___***FUNCTIONS***___ in __JS__ _____________________________________________
+ 1. Function Declaration
```python
    function $name_function(width, height){
        return width * height;
    }
    console.log($name_function(5, 6));
    // Expected output: 30;

    console.log($name_function(10, 20));
    // Expected output: 200
```

+ 2. Function Expression
>It divides into two type:
>> + 1. `Anonymous` 
>> ```python
>> let anonymous = function(parametrs){
>> return parametrs;
>>} 
>>```
>> + 2. `Arrow`
>>```python
>> let arrow = (parametrs) => {
>>return parametrs;
>>}
>>```

+ 3. Function IIFE(Immediately Invoked Function Expression)
```python
    let name = Nizomi;

    (function(a, b){
        let name = Izzatullo;
        console.log(name) // Izzatullo
    })()
    console.log(name) // Nizomi
```

<br>
<h1 style = "font-size: 130px; color: #1515"><i><b>Thank you!</h1>