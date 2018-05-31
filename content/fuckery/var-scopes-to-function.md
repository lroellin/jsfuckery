---
title: "var scopes to function"
date: 2018-01-07T13:30:02+01:00
githubUsername: "lroellin"
---

```js
function foo() {
    {
        var x = 5
        let y = 6
        const z = 7
    }
    console.log(x)
    console.log(y)
    console.log(z)
}
foo() // 5, undefined, undefined
```
