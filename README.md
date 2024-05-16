
<https://vuepress.github.io/zh/>

<https://theme-hope.vuejs.press/zh/>

```bash
# 设置代理
pnpm config set proxy http://127.0.0.1:7890
# 配置安装及缓存路径
pnpm config set store-dir "C:\data\pnpm\store"
pnpm config set global-dir "C:\data\pnpm\global"
pnpm config set global-bin-dir "C:\data\pnpm\global-bin"
pnpm config set state-dir "C:\data\pnpm\state"
pnpm config set cache-dir "C:\data\pnpm\cache"
# 安装vuepress-theme-hope
pnpm create vuepress-theme-hope [dir]

# 启动
pnpm docs:dev
# 构建
pnpm docs:build
```
