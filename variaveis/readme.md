# Variáveis 
[Developers Mozilla](https://developer.mozilla.org/pt-BR/docs/Web/JavaScript/Reference/Statements/var)
```
var loop = 10;

for (var index = 0; index < loop; index++) {
  console.log(`Index: ${index}, loop: ${loop}`);
}
```

# Let
[Developers Mozilla](https://developer.mozilla.org/pt-BR/docs/Web/JavaScript/Reference/Statements/let)
```
for (let index = 0; index < 10; index++) {
  console.log(`Index: ${index}`);
}

// ReferenceError: index is not defined
console.log(`Index depois do loop: ${index}`);
```

# Const
[Developers Mozilla](https://developer.mozilla.org/pt-BR/docs/Web/JavaScript/Reference/Statements/const)

```
const PI = 3.14
```