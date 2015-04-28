Tricks for naked js
===================

bind included document.querySelector to dollar

```js
var d = document
var $ = d.querySelector.bind(d);
```

