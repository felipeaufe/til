# Spread operator

With the Spread operator the handling of arrays has never been simpler, which previously required a few lines of code, now with only '...' we optimize the time with coding and maintenance.

### Concatenate two arrays

```javascript
const middle = [3, 4];
const arr = [1, 2, ...middle, 5, 6];
console.log(arr);
// [1, 2, 3, 4, 5, 6]
```
```javascript
var arr = [1, 2];
var arr2 = [3, 4];
arr = [...arr, ...arr2];
console.log(arr);
// [1, 2, 3, 4]
```

### Copying arrays

```javascript
const arr = ['a', 'b', 'c'];
const arr2 = [...arr];
console.log(arr2);
// ['a', 'b', 'c']
```

See the [Spread operator - tutorial](https://www.luiztools.com.br/post/4-segredos-do-operador-spread-em-javascript/)
on LuizTools.com.br for more details.