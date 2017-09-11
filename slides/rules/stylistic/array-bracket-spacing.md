#### 1.0 禁止在数组括号两边出现空格
```javascript

// bad
var arr = [ 'foo', 'bar' ];
var arr = ['foo', 'bar' ];

var [ x, y ] = z;
var [ x,y ] = z;


// good
var arr = [];
var arr = ['foo', 'bar', 'baz'];

var [x, y] = z;
var [x,y] = z;
```