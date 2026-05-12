# BEEBEST Helmet Intercom Architecture

这是一个面向开发者的技术文档仓库，整理了“极蜂头盔对讲耳机”这类产品的可复刻实现方案。

文档入口：

- [极蜂头盔对讲耳机复刻实现技术文档](./beebest-helmet-intercom-architecture.md)

## 文档内容

本文档覆盖以下主题：

- BLE 管理通道与经典蓝牙音频通道的双模架构
- 主耳机、后座耳机、手机 App 的职责拆分
- 前后座配对与自动重连状态机
- MESH 组队、多人通话、后座挂靠进群模型
- iOS / Android 客户端边界
- 固件模块划分、GATT 设计、命令协议建议
- 容量、时延、兼容性与测试方案

## 资料边界

文档内容分为两部分：

- 官方公开资料可确认的产品能力
- 在缺少厂商内部协议文档时，给出的最佳工程实现方案

因此，这不是对极蜂内部实现的逆向结论，而是一份面向复刻落地的架构设计文档。

## Mermaid 支持

仓库文档中的流程图、时序图、状态机图使用 `Mermaid` 编写。GitHub 支持直接渲染这些代码块。

如果你要把文档同步到不支持 Mermaid 的平台，例如飞书，建议：

- 保留 Markdown 源文件在 GitHub
- 将 Mermaid 图导出为 `PNG` 或 `SVG`
- 再把导出的图片贴到目标平台

## 来源

- [极蜂对讲 App Store 页面](https://apps.apple.com/cn/app/%E6%9E%81%E8%9C%82%E5%AF%B9%E8%AE%B2/id1662805520)
- [极蜂头盔对讲耳机官网](https://www.ifengyu.com/)
- [BEEBEST 极蜂产品页](https://www.ifengyu.com/home)
