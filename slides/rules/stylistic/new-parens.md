#### 2.5 要求调用无参构造函数时带括号
```javascript

// bad
var person = new Person;
var person = new (Person);

// good
var person = new Person();
var person = new (Person)();
```