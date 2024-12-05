# eslint-prettier-husky

## ESLint

https://eslint.org/

## eslint-config-airbnb

https://www.npmjs.com/package/eslint-config-airbnb

```shell
mkdir eslint-prettier-husky
cd eslint-prettier-husky
code .

npm init -y
# @Note: eslint.config.mjs
npm i -D eslint

npx eslint app.js
or
npm run lint

# eslint-config-airbnb
npm i -D eslint-config-airbnb
  npm ERR! code ERESOLVE
  npm ERR! ERESOLVE unable to resolve dependency tree
  npm ERR!
  npm ERR! While resolving: eslint-prettier-husky@1.0.0
  npm ERR! Found: eslint@9.16.0
  npm ERR! node_modules/eslint
  npm ERR!   dev eslint@"^9.16.0" from the root project
  npm ERR!
  npm ERR! Could not resolve dependency:
  npm ERR! peer eslint@"^7.32.0 || ^8.2.0" from eslint-config-airbnb@19.0.4
  npm ERR! node_modules/eslint-config-airbnb
  npm ERR!   dev eslint-config-airbnb@"*" from the root project
  npm ERR!
  npm ERR! Fix the upstream dependency conflict, or retry
  npm ERR! this command with --force or --legacy-peer-deps
  npm ERR! to accept an incorrect (and potentially broken) dependency resolution.
  npm ERR!
  npm ERR!
  npm ERR! For a full report see:
  npm ERR! C:\Users\homur\AppData\Local\npm-cache\_logs\2024-12-04T18_56_53_543Z-eresolve-report.txt

  npm ERR! A complete log of this run can be found in: C:\Users\homur\AppData\Local\npm-cache\_logs\2024-12-04T18_56_53_543Z-debug-0.log

# eslintのバージョンをダウングレードする
npm uninstall eslint
npm install -D eslint@^8.2.0
# 再実行
npm i -D eslint-config-airbnb
npm i -D eslint-config-airbnb-base
```

## Prettier

https://prettier.io/

```shell
# prettier
npm i -D prettier
```

## VScode 拡張機能

- Prettier - Code formatter
- ESLint

## Husky

https://typicode.github.io/husky/get-started.html

```shell
npm install husky lint-staged --save-dev
```

# Notes

````shell
# eslint-config-airbnbの最新バージョンを確認する
npm info eslint-config-airbnb
s```
````
