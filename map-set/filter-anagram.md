---
title: 'Filter anagram'
Question: https://javascript.info/task/filter-anagrams
category: 'Map and Set'
---

Looping through array, reorgnize each element with toLowerCase, split, sort, join methods

```js
function aclean(arr) {
  let map = new Map();
   arr.forEach(elem => {
    const key = elem.toLowerCase().split('').sort().join('')
    map.set(key, elem);
  })
  return Array.from(map.values());
}
let arr = ["nap", "teachers", "cheaters", "PAN", "ear", "era", "hectares"];

console.log(aclean(arr))
```