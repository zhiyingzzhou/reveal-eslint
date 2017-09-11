#### 1.2 强制在代码块中使用一致的大括号风格
```javascript

// bad
// Allman风格
// 括号必须单独成行且没有任何缩进
if(foo)
{
bar();
}
else
{
baz();
}
// Stroustrup风格
//if-else中的else语句，连同catch 和 finally，都必须在右括号后另起一行
if (foo) {
  bar();
}
else {
  baz();
}

// good
// one true brace style 风格
// 它将大括号放在控制语句或声明语句同一行的位置
if (foo) {
  bar();
} else {
  baz();
}
```