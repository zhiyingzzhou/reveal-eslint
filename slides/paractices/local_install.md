<h4>3.1 本地安装</h4>
```javascript

// 如果你想让 ESLint 成为你项目构建系统的一部分，我们建议在本地安装。

$ npm install eslint --save-dev

// 紧接着你应该设置一个配置文件：
// 改命令执行完毕后，会在当前项目根目录下生成.eslitrc.js文件
$ ./node_modules/.bin/eslint --init

// 之后，你可以在你项目根目录运行 ESLint：

$ ./node_modules/.bin/eslint yourfile.js

```