#### 1.6 要求一致的 This
该规则指定一个变量作为 this 的别名(变量声明默认为_this )。它将强制两件事情：
* 如果一个变量声明为一个指定的名称，它 必须 初始化（在声明语句中）或被赋值（与声明语句在同一范围内）为 this。
* 如果一个变量初始化或被赋值为 this，那么该变量 必须 是指定的别名。

```javascript

// bad
const _this = 42;
const self = this;

// good
const  _this = this;
```