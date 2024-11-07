# create-yzc-app

create a yzc app project with gitlab template

## 本地调试

```bash
npm run dev
```

此命令会打包生成 dist 目录，其中包含 index.mjs

会在 dev 编译后，自动使用 node 执行`node ./dist/index.mjs`此文件进行调试

## 打包发布

执行打包发布命令

```bash
npm publish
```

此命令执行时，会自动先执行`npm run build & npm version patch`
