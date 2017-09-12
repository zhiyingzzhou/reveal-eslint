#### 1.3 强制在逗号周围使用空格
*禁止在逗号前使用空格，要求在逗号后使用一个或多个空格*
```javascript

// bad
var foo = 1 ,bar = 2;
var arr = [1 , 2];
var obj = {"foo": "bar" ,"baz": "qur"};

// good
var foo = 1, bar = 2
    , baz = 3;
var arr = [1, 2];
var arr = [1,, 3]
var obj = {"foo": "bar", "baz": "qur"};
```