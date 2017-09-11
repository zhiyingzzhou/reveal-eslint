#### 3.7 要求语句块之前的空格
```javascript

// Bad
if (a){
    b();
}

function a(){}

for (;;){
    b();
}

// Good
if (a) {
    b();
}

if (a) {
    b();
} else{ /*no error. this is checked by `keyword-spacing` rule.*/
    c();
}
```