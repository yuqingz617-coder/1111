# Next.js 项目

使用 Next.js App Router、TypeScript 和 Tailwind CSS。

## 环境要求

Node.js 20.9 或更新版本（当前已验证 Node.js 24），npm。

## 安装和开发

```bash
npm ci
npm run dev
```

首页位于 `src/app/page.tsx`，全局布局和样式位于 `src/app/layout.tsx` 和 `src/app/globals.css`。
项目使用系统字体，构建无需下载 Google Fonts。

## 检查和生产运行

```bash
npm run lint
npm run build
npm run start
```

在云环境中若默认 npm 缓存目录不可写，可为安装命令设置
`npm_config_cache=/tmp/1111-npm-cache`。
