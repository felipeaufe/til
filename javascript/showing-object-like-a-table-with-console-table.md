# Table in console

It is possible to display on the console a set of objects with a similar structure in `table` format using console.table surrounded by square brackets.

```javascript
const jon = { name: 'Jony', age: 30, happy: true }
const fel = { name: 'Felipe', age: 29, happy: true }
const ana = { name: 'Ana', age: 33, happy: true, active: false }

console.table([ jon, fel, ana ]);

```

See the [Console.table() docs](https://developer.mozilla.org/pt-BR/docs/Web/API/Console/table)
on MDN for more details.