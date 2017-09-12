#### 4.4 禁止变量在定义前使用
```javascript

// bad
alert(a);
var a = 10;

// good
var a;
a = 10;
alert(a);

```