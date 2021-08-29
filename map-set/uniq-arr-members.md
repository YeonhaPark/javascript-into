---
title: 'Filter anagram'
Question: https://javascript.info/task/array-unique-map
category: 'Map and Set'
---

```js
function unique(arr) {
  const set = new Set(arr);
   const uniqArr = [];
   set.forEach(item => uniqArr.push(item));
   return uniqArr;
 }
 
 let values = ["Hare", "Krishna", "Hare", "Krishna",
   "Krishna", "Krishna", "Hare", "Hare", ":-O"
 ];
 
 
 console.log(unique(values));

// Another solution
function unique2(arr) {
 return Array.like(new Set(arr));
 }
```