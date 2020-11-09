---
layout: news
title: "关于移除 Deepin 镜像中部分内容的通知"
date: 2020-10-29
author: TUNA Staff
category: news
---

我们接到了热心用户的反馈，指出镜像站上 Deepin 镜像中含有第三方的商业软件。
经检查，发现 Deepin 镜像中含有的部分第三方的商业软件涉及其重分发授权问题，
我们缺乏理由相信这些商业软件的权利人允许镜像站重新分发这些软件。

在缺乏授权的情况下，我们无法保证镜像的合规性与服务质量。因此我们决定，在重分发授权问题解决之前，
移除 Deepin 镜像中的部分内容和 Deepin 的安装镜像。具体情况如下：

* 停止 `deepin-cd` 的镜像服务；
* 移除 `deepin` 镜像中的下列目录：
  - `/pool/non-free`;
  - `/dists/*/non-free`。

如果现有用户有需要使用上述目录中的软件包，请切换至官方上游，以防影响正常使用。

感谢您的理解与支持！