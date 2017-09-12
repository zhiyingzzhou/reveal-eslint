#### 1.4 强制使用一致的逗号风格
*要求逗号放在数组元素、对象属性或变量声明之后，且在同一行*
```javascript

// bad
var foo = 1
,
bar = 2;

var foo = 1
  , bar = 2;

// good
var foo = 1, bar = 2;

var foo = 1,
    bar = 2;
```