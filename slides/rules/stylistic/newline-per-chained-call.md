#### 2.6 要求方法链中每个调用都有一个换行符
```javascript

// bad
d3.select("body").selectAll("p").style("color", "blue");

// good
d3
    .select("body")
    .selectAll("p")
    .style("color", "white");
```