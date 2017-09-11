#### 3.0 禁止可以表达为更简单结构的三元操作符
```javascript

// Bad
// 两个 Boolean 值之间进行选择而不是使用！将测试条件转为一个 Boolean 类型
var isYes = answer === 1 ? true : false; 
// 使用单个变量同时作为判断条件和结果
var foo = bar ? bar : 1; 

// Good
var isYes = answer === 1;
var foo = bar || 1;
```