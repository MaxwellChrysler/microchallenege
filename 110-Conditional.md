# Conditional Checkpoint
Create a function that takes two numbers.

If the first number is bigger than the second number, return `"The first number was bigger!"`.
If the second number is bigger than the first number, return `"The second number was bigger!"`.
If the numbers are the same, return `"The numbers are the same!"`.

## Examples:

### Example 1

```js

function compare (firstNumber, secondNumber){
    if (firstNumber>secondNumber){
        return "the first number was bigger";
    }
    else if (furstNumber<secondNumber){
     return "the second number was bigger";
    }
    else {
        return "the numbers are the same!"
    }
}
let result = yourFunction(3, 2)
console.log(result);
```

should log 

```
The first number was bigger!
```

### Example 3

```js
let result = yourFunction(2, 7)
console.log(result);
```

should log


```
The second number was bigger!
```

### Example 2

```js
let result = yourFunction(7, 7);
console.log(result);


function compare (firstNumber, secondNumber){
    if (firstNumber>secondNumber){
        return "the first number was bigger!";
    }
    else if (firstNumber<secondNumber){
     return "the second number was bigger!";
    }
    else {
        return "the numbers are the same!"
    }
}
let result = compare(3, 2)
console.log(result);
result = compare(2, 7)
console.log(result);
result = compare(7, 7);
console.log(result);