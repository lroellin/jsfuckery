---
title: "var Scopes to Function"
date: 2018-01-07T13:30:02+01:00
githubUsername: "lroellin"
---

```js
function foo() {
    {
        var x = 5
    }
    console.log(x) // 5
}
```