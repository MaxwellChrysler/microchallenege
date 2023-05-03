# Array Checkpoint

Create a function that takes in an array. Add up the first and last values in the array.

## Examples:

### Example 1

```js

function addArray(array){
    return array[0]+array[array.length-1];//make sure the minus 1 is in the array location lol otherwise it will return not a number
}

let result = addArray([1, 2, 3, 4, 5]);
console.log(result);






 result = addArray([6, 7, 8, 9, 10, 11, 12]);
console.log(result);
```

should log


```
18
```


