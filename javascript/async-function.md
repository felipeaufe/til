# Async function

A great way to work in sync without nesting promises or using callback functions is using `async` function

```javascript

const sumRandomAsyncNums = async () => {
    const first = await random(){};
    const second = await random(){};
    const third = await random(){};

    console.log(`Result ${first + second + third}`);
}

```

See the [Async function - doc](https://developer.mozilla.org/pt-BR/docs/Web/JavaScript/Reference/Statements/funcoes_assincronas)
on MDN for more details.