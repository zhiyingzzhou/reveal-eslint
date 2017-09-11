#### 1.0 要求 Switch 语句中有 Default 分支
```javascript

// bad
switch (foo) {
    case 1:
        doSomething();
        break;
    case 2:
        doSomething();
        break;
    // no default
}

// good
switch (foo) {
    case 1:
        doSomething();
        break;
    case 2:
        doSomething();
        break;
    default:
        // do nothing
}
```