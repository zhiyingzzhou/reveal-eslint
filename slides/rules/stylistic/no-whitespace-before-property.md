#### 3.1 禁止属性前有空白
```javascript

// Bad
foo [bar]

foo. bar

foo .bar

foo. bar. baz

// Good
foo.bar

foo[bar]

foo[ bar ]

foo.bar.baz
```