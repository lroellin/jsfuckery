---
title: "Automatic  Global Scope"
date: 2018-01-07T13:20:09+01:00
author: "github.com/lroellin"
---

Variables without any qualifier (`var`, `let`/`const`) are automatically in the global scope

```js
console.log(x) // x is not defined
function foo() {
    x = 5
}
foo()
console.log(x) // 5
```