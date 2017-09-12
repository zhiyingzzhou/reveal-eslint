<h4>3.2 全局安装</h4>
```javascript

// 如果你想使 ESLint 适用于你所有的项目，我们建议你全局安装 ESLint。

$ npm install -g eslint

// 紧接着你应该设置一个配置文件：
// 改命令执行完毕后，会在当前目录下生成.eslitrc.js文件
$ eslint --init

// 之后，你可以在任何文件或目录运行 ESLint：

$ ./node_modules/.bin/eslint yourfile.js

```