# create-yzc-app

create a yzc app project with gitlab template

## 本地调试

```bash
npm run dev
```

此命令会打包生成 dist 目录，其中包含 index.mjs

```bash
node ./dist/index.mjs
```

node 执行此文件进行调试

## 打包发布

执行打包命令

```bash
npm run build
npm version patch
npm publish
```
