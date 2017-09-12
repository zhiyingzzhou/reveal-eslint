#### 4.6 要求使用点号
*在 JavaScript 中，你可以使用点号 (foo.bar) 或者方括号 (foo["bar"])来访问属性。然而，点号通常是首选，因为它更加易读，简洁，也更适于 JavaScript 压缩。*
```javascript

// bad
var x = foo["bar"];

// good
var x = foo.bar;
var x = foo[bar];    // Property name is a variable, square-bracket notation required
```