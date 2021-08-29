## Array.from

<b>It can be used when using Set, to convert array-like object to an array.</b>

The Array.from() static method creates a new, shallow-copied Array instance from an array-like or iterable object.

```js
console.log(Array.from('foo'));
// expected output: Array ["f", "o", "o"]

console.log(Array.from([1, 2, 3], x => x + x));
// expected output: Array [2, 4, 6]
```

- Parameters
1) arrayLike
An array-like or iterable object to convert to an array.

2) mapFn (Optional)
Map function to call on every element of the array.

3) thisArg (Optional)
Value to use as this when executing mapFn

- Return value
A new Array instance.

https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Array/from
