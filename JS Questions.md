### Question No: 1

```js
var y = 5;

function log() {
  x = 4;
  console.log(`y: ${y}`);
}

log();
console.log(`x: ${x}`);
```

What will be the value of x and y in the above code block?

---

### Question No: 2

What type of inheritance ES6 has: (choose correct answers)

1. Class based inheritance
2. Prototypal inheritance
3. Function based inheritance

---

### Question No: 3

```js
let x = 10;
let y = 5;
```

Write a function that will swap x and y values without using a temporary variable?

---

### Question No: 4

Which programming paradigms JavaScript supports? (choose correct answers)

1. Imperative
2. OOP
3. Functional Programming

---

### Question No: 5

```js
const names = [
  { id: 1, name: "Rakib" },
  { id: 2, name: "Fahim" },
  { id: 3, name: "Rasel" }
];

const phones = [
  { id: 1, number: "01711885599" },
  { id: 2, number: "01911823599" },
  { id: 3, number: "01812885599" }
];
```

Write a function that will take two array as args and return an array of objects containing name and number by matching ids from both array.

---

### Question No: 6

Nodejs is a: (choose correct answers)

1. JS Runtime environment
2. Blocking I/O
3. Event driven
4. JavaScript Framework

---

### Question No: 7

```js
const obj = {
  a: 1,
  b: 2,
  c: {
    age: 30
  }
};

const objClone = Object.assign({}, obj);
objClone.b = 4;
objClone.c.age = 30;
```

What will be the value of `obj.b` and `obj.c.age` ?

---

### Question No: 8

```js
const arr1 = [5, 6, 9, 2];
const arr2 = [8, 2, 1, 2];
```

Write a function that will take this two array as args and return an array of unique numbers.

---

### Question No: 9

The value of `this` keyword in `fat arrow` function defined: (choose correct answers)

1. By Lexical Scope
2. By Function's Execution Context
3. By Global Scope

---

### Question No: 10

```js
const ar = [1, [2], [3, [[4]]]];
```

Flatten the nested array. Your output should look like this:
`[1,2,3,4]`

---

### Question No: 11

Suppose you are designing a details page of product in React. The page url is `/products/[productId]`. Now, in which life cycle methods you should fetch and update the data depending on `productId`. (choose correct answers)

1. componentDidMount
2. shouldComponentUpdate
3. componentDidUpdate
4. componentWillReceiveProps
5. getSnapshotBeforeUpdate

---

### Question No: 12

Convert this **Callback Hell** to a more readable approach.

```js
fetchData("api/users/rakib-ahmed", function(result) {
  fetchData(`api/users/${result.userId}/posts/`, function(result) {
    fetchData(
      `api/users/${result.userId}/posts/${result.postIds}/comments`,
      function(result) {
        fetchData(`api/users/${result.userId}/stats/`, function(result) {
          // Callback hell
        });
      }
    );
  });
});
```
