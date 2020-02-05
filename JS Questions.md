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

What is Lexical scoping?

---

### Question No: 3

```js
x = 10;
y = 5;
```

How to swap x and y values without using a temporary variable?

---

### Question No: 4

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

### Question No: 5

Node.js is a JS runtime, event-driven and non-blocking I/O built using Chrome’s V8 JavaScript engine.

Here, explain the term **non-blocking I/O** ?

---

### Question No: 6

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

- What will be the value of `obj.b` and `obj.c.age` ?
- How **reference type** works in Javascript?

---

### Question No: 7

```js
const arr1 = [5, 6, 9, 2];
const arr2 = [8, 2, 1, 2];
```

Write a function that will take this two array as args and return an array of unique numbers.

---

### Question No: 8

How `this` keywords works in `fat arrow` function?

---

### Question No: 9

```js
const ar = [1, [2], [3, [[4]]]];
```

Flatten the nested array. Your output should look like this:
`[1,2,3,4]`

---

### Question No: 10

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
