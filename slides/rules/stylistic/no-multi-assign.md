#### 2.8 禁止使用链式赋值表达式
```javascript

// bad
var a = b = c = 5;

var foo = bar = "baz";

var a =
    b =
    c;

// good
var a = 5;
var b = 5;
var c = 5;
```