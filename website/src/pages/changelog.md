---
layout: ../layouts/BaseLayout.astro
title: 更新记录
description: Rolume public beta changelog and release notes.
---

# 更新记录

## Rolume 1.1

小范围公开测试版本。

### 下载

- [Rolume.dmg](https://github.com/ericcilcn/Rolume/releases/download/1.1/Rolume.dmg)
- SHA-256：`b2f1baf19138105db9237b75bd74dc8a3814e97a9de6780df721a9994aa7e621`

### 主要变化

- 项目从 `MacVolumeControl` 更名为 `Rolume`
- 重构外接显示器 DDC/CI 音量控制逻辑
- 鼠标和触控板改为独立音量控制设置
- 支持鼠标和触控板分别设置步进幅度和修饰键
- 静音后普通音量调节不再自动解除静音
- 调整触控板默认控制区域，减少 Dock 区域误触
- 改进辅助功能权限请求流程
- 调整 OSD 位置、尺寸、圆角和设备名布局
- 重做 DMG 安装包并补充 SHA-256 校验值

完整更新内容可以查看仓库根目录中的 `CHANGELOG.md`。
