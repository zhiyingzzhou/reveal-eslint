#### 2.7 禁止使用 空格 和 tab 混合缩进
```javascript

// bad
function main() {
// --->var x = 5,
// --->....y = 7;

    var x = 5,
        y = 7;
}

// good
function add(x, y) {
// --->return x + y;
    return x + y;
}
```