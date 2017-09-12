* 在根目录下新建hooks目录，新建pre-commit文件，如下：

```javascript
#!/bin/bash

for file in $(git diff --cached --name-only | grep -E '\.(js|jsx)$')
do
  git show ":$file" | node_modules/.bin/eslint -c .eslintrc.js --stdin --stdin-filename "$file" # we only want to lint the staged changes, not any un-staged changes
  if [ $? -ne 0 ]; then
    echo "ESLint failed on staged file '$file'. Please check your code and try again. You can run ESLint manually via npm run eslint."
    exit 1 # exit with failure status
  fi
 done
```

* 在package.json中的scripts中添加如下命令：

```javascript

"hookinstall": "node ./node_modules/copy/bin/cli.js ./githooks/* ./.git/hooks/"
```