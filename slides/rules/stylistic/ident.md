#### 1.9 强制使用一致的缩进。默认是 4个空格。

```javascript

// bad
if (a) {
  b=c;
  function foo(d) {
    e=f;
  }
}

// good
if (a) {
    b=c;
    function foo(d) {
        e=f;
    }
}
```