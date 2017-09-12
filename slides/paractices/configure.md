<h4>3.3 配置eslint</h4>
* 执行完eslint init后，会自动在当前目录下生成一个.eslitrc.js文件。我们可以在这个文件中开启或关闭规则。
<img src="./resources/eslintrc.png" />

* 示例：

```javascript
{
    "rules": {
        // 语句后面始终必须有分号
        "semi": ["error", "always"]
    }
}
```

* Eslint每个规则都有三个等级：
<p style="font-size: 1rem;">1."off" 或 0 - 关闭规则</p>
<p style="font-size: 1rem;">2."warn" 或 1 - 开启规则，使用警告级别的错误：warn (不会导致程序退出)</p>
<p style="font-size: 1rem;">3."error" 或 2 - 开启规则，使用错误级别的错误：error (当被触发的时候，程序会退出)</p>