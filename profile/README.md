# 声核 Audcore

轻巧的 Windows 实时调音台：连接音频设备，组合 VST3 效果器，让麦克风、伴奏和监听各走各的通道。

- [官网与下载](https://audcore.utae.cn/)
- [使用指北](https://audcore.utae.cn/guide/)
- [文档、更新与问题反馈](https://github.com/audcore/audcore-document)
- [社区讨论](https://github.com/audcore/audcore-document/discussions)
- [皮肤开发入口 · skin-dev](https://audcore.utae.cn/skin-dev/)
- [皮肤项目列表](https://github.com/audcore/audcore-document/blob/main/skins.md)
- [皮肤开发与发布规范](https://github.com/audcore/audcore-document/blob/main/docs/皮肤发布规范.md)

## 参与皮肤开发

每款皮肤在本组织的独立仓库维护。manifest.json 统一记录身份、版本、语言和构建方法，README 提供介绍及使用说明。初次收录通过资料仓库 skins.md 的 PR 人工审核；在线版本以官方签名列表为准。

声核本体源码目前不在这些公开仓库中；这里提供文档、皮肤源码和开发参考。

## 按界面选择皮肤源码

| 界面 | 用途 | 仓库 |
| --- | --- | --- |
| 表格调音台 | 每列一个通道，效果器和发送按行对齐。 | [源码](https://github.com/audcore/audcore-skin-spreadsheet-mixer) |
| 通道条调音台 | 各通道横向并列，便于比较音量、电平和状态。 | [源码](https://github.com/audcore/audcore-skin-channel-strip-mixer) |
| 横向机架调音台 | 通道按横向机架行排列，避免所有信息挤在窄通道条里。 | [源码](https://github.com/audcore/audcore-skin-rack-mixer) |
| 节点连线调音台 | 拖动节点整理布局，用滚轮缩放，按住空格拖动画布。 | [源码](https://github.com/audcore/audcore-skin-node-routing) |
| 录音棚调音台 | 采用录音台式面板，将效果器、发送和推子按区域排列。 | [源码](https://github.com/audcore/audcore-skin-recording-console) |
| X AIR 数字调音台 | 窄通道条并列显示，推子沿用 X AIR 风格的刻度。 | [源码](https://github.com/audcore/audcore-skin-xair-mixer) |
| 电平仪表盘 | 荧光绿配色配合醒目的电平与数值，方便观察信号状态。 | [源码](https://github.com/audcore/audcore-skin-meter-dashboard) |
| 直播操作台 | 将常用通道置顶，减少直播时查找通道的操作。 | [源码](https://github.com/audcore/audcore-skin-live-control) |
| 命令终端调音台 | 输入 help 查看命令，使用 use 切换当前通道。 | [源码](https://github.com/audcore/audcore-skin-command-terminal) |
| Windows 98 桌面调音台 | 采用 Windows 98 风格的桌面、任务栏和窗口控件。 | [源码](https://github.com/audcore/audcore-skin-windows98-desktop) |
| TTPlayer 三窗口调音台 | 主窗口控制所选通道的音量与静音，并显示实时左右电平。 | [源码](https://github.com/audcore/audcore-skin-ttplayer-mixer) |
| 悬浮菜单调音台 | 拖动悬浮图标调整位置，右键或菜单键打开操作菜单。 | [源码](https://github.com/audcore/audcore-skin-floating-menu) |
