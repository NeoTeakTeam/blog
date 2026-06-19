---
title: 第一次使用 Hexo
date: 2026-06-19 19:47:37
tags:
    - Hexo
categories:
    - 萌新
---

最近尝试将我的 jekyll 博客迁移到 hexo 上，因为 hexo 是一个非常方便的博客框架，它的配置文件简单，插件丰富，文档详细。

正好也可以和大家分享一下我的 hexo 折腾历程。

## 配置环境

只需要一个 `node.js` 环境，就可以开始使用 hexo 了。

不过，你还需要一个 `npm`，但我更倾向于使用 `pnpm`。并且往后的内容中我也会使用 `pnpm` 代替 `npm`。

### 安装 `hexo-cli`

```bash
pnpm install hexo-cli -g
```

## 创建项目

```bash
hexo init <你的Blog名称>
cd <你的Blog名称>
```

如果你使用 `pnpm` 的话，请使用以下命令来创建：

```bash
hexo init <你的Blog名称> --no-install
cd <你的Blog名称>
pnpm install
```

## 配置博客

完成后，你可以通过自定义 `_config.yml` 的方式来配置你的博客信息。

## Hexo 的优缺点

优点:
- 使用 `node.js` + `npm/pnpm` 即可运行，方便管理与更新
- 配置文件简单，插件丰富，文档详细

缺点:
- 没有热重载（哭
