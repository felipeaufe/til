# Table in console

It is possible to extract attributes from within arrays and objects using the attribute `destructuring`, in this way we are able to extract only what will be used or simply send only what is necessary to a function for example.

```javascript
const turtle = {
    name: 'Jony',
    legs: 4,
    shell: true,
    type: 'amphibious',
    meal: 10,
    diet: 'berries'
}

function feed(animal){
    const { name, meal, diet } = animal;
    return `Feed ${name} ${meal} kilos of ${diet}`;
};

feed(turtle);
// "Feed Jony 10 kilos of berries"

```

See the [Destructuring assignment docs](https://developer.mozilla.org/pt-BR/docs/Web/JavaScript/Reference/Operators/Atribuicao_via_desestruturacao)
on MDN for more details.