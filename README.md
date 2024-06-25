# doc-otter-trade

https://OtterTrade.com 的文档站，在这里你将找到关于 OtterTrade 的一切。

该仓库编译后推送到 Github 仓库:

https://github.com/otter-trade/otter-trade.github.io

可以访问 GitHub Pages 进行查看

https://otter-trade.github.io

同时也会通过 Webhooks 部署在以下站点

https://doc.ottertrade.com

https://ot-doc.mo7.cc

## 博客框架

https://v2.vuepress.vuejs.org/

基于 [VuePress Theme Hope](https://theme-hope.vuejs.press) 搭建

## 评论服务

文档\
https://waline.js.org

服务地址\
https://talk.mo7.cc

管理后台(Github 登录)
https://talk.mo7.cc/ui

## 图标库 ot-doc

https://www.iconfont.cn/manage/index?spm=a313x.7781069.1998910419.22&manage_type=myprojects&projectId=4563845

## 运行

运行环境:

node 版本: v20.x

pnpm 版本: 9.x

```bash

# 启用 pnpm
npm install -g pnpm

# 安装依赖
pnpm install

# 更新依赖
pnpm run update-package

# 本地运行
pnpm run dev

# 编译打包
pnpm run build

# 更新同步至 <https://github.com/otter-trade/doc-otter-trade>
pnpm run sync

# 打包并推送至 <https://github.com/otter-trade/otter-trade.github.io> 仓库
pnpm run deploy

```
