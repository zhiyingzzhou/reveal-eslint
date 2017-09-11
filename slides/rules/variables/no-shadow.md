#### 1.0 禁止变量声明覆盖外层作用域的变量
```javascript

// bad
var a = 3;
function b() {
    var a = 10;
}

// good
var a = 3;
function b() {
    a = 10;
}
```