# Debugging 

The most interesting way to identify `objects` when using console.log is to add variables to an object, in this way the name of the `object` will be displayed in the console.

```javascript
const jon = { name: 'Jony', age: 30, happy: true }
const fel = { name: 'Felipe', age: 29, happy: true }
const ana = { name: 'Ana', age: 33, happy: true }

console.log({ jon, fel, ana });

// {jon: {…}, fel: {…}, ana: {…}}
// ana: {name: "Ana", age: 33, happy: true}
// fel: {name: "Felipe", age: 29, happy: true}
// jon: {name: "Jony", age: 30, happy: true}

```

See the [console.log() docs](https://developer.mozilla.org/en-US/docs/Web/API/Console/log)
on MDN for more details.