# Spread operator


```javascript

// Concatenate two arrays.
const middle = [3, 4];
const arr = [1, 2, ...middle, 5, 6];
console.log(arr);
// [1, 2, 3, 4, 5, 6]

var arr = [1, 2];
var arr2 = [3, 4];
arr = [...arr, ...arr2];
console.log(arr);
// [1, 2, 3, 4]

// Copying arrays
JavaScript
const arr = ['a', 'b', 'c'];
const arr2 = [...arr];
console.log(arr2);
// ['a', 'b', 'c']


```

See the [Destructuring assignment docs](https://developer.mozilla.org/pt-BR/docs/Web/JavaScript/Reference/Operators/Atribuicao_via_desestruturacao)
on MDN for more details.