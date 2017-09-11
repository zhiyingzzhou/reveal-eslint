#### 3.5 要求对象字面量属性名称使用引号
```javascript

// Bad
var object = {
    foo: "bar",
    baz: 42,
    "qux-lorem": true
};

// Good
var object1 = {
    "foo": "bar",
    "baz": 42,
    "qux-lorem": true
};
```