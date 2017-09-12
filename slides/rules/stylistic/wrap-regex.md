#### 3.9 要求正则表达式被包裹起来 
```javascript

// Bad
// 在某些情况下，使用正则表达式时，它看起来会像一个除法运算符
function a() {
    return /foo/.test("bar");
}

// Good
function a() {
    return (/foo/).test("bar");
}
```