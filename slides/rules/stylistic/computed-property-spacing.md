#### 1.5 禁止在计算属性中使用空格
```javascript

// bad
obj[ foo ]
obj[ 'foo' ]
var x = {[ b ]: a}
obj[ foo[ bar ] ]

// good
obj[foo]
obj['foo']
var x = {[b]: a}
obj[foo[bar]]
```