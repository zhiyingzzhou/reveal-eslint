#### 1.1 强制在单行代码块中使用空格
```javascript

// bad
function foo() {return true;}
if (foo) { bar = 0;}


// good
function foo() { return true; }
if (foo) { bar = 0; }
```