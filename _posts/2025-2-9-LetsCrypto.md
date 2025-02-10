---
title: Let's crypto
description: Let's encrypt together!
author: AImixAE Mocha
date: 2025-2-9 21:00:00 +0800
categories: [Software]
tags: [encrypt, software]
image:
    path: /assets/img/posts/2025-2-9-LetsCrypto/St0.png
---

# Let's crypto

Let's encrypt together!

## Info

这是一个简单的加解密程序。我们开发了一些工具来使用它。

我们使用C#编写了这些工具。我们开发了一个跨平台的控制台程序和一个仅支持Windows的图形工具来使用它。

在开发它的第一天，我设定了一个目标。努力在一天内完成所有项目。

最终，我们在 2025/2/9 18:30 左右完成了所有项目 *(详细见 这个[Commit](https://github.com/NeoTeakTeam/letscrypto/commit/e748ee20ea2f88221734ed89a53d03739103bdad))*。

这个项目是我第一次使用C#开发的，也就作为我学习C#的一个项目吧。

## 安装

首先，你需要克隆这个仓库。

```bash
git clone https://github.com/NeoTeakTeam/letscrypto.git
```

并且确保你有 .NET Core 9.0 及以上的版本。

然后你就可以进入项目里编译了。

```bash
# Console
cd letscrypto/letscrypto-cli-all
dotnet build

# GUI (windows only)
cd letscrypto/letscrypto-gui-windows
dotnet build
```

最终，你就可以运行了。

## 使用

使用这些工具十分简单，你只需要打开这些程序即可，然后看看说明。

![St0](/assets/img/posts/2025-2-9-LetsCrypto/St0.png)
![St1](/assets/img/posts/2025-2-9-LetsCrypto/St1.png)

## 帮助我们

如果你有任何问题或建议，请随时联系我们。

但由于我的学业，我不得不暂时停止这个项目。如果你愿意，你可以帮助我继续维护这个项目。
