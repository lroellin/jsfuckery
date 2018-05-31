---
title: "Automatic  Global Scope"
date: 2018-01-07T13:20:09+01:00
githubUsername: "lroellin"
---

Variables without any qualifier (`var`, `let`/`const`) are automatically in the global scope (after executing the block)

```js
console.log(x) // x is not defined
function foo() {
    x = 5
}
// x is still not defined
foo()
console.log(x) // 5
```
