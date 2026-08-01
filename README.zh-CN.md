# Quota Blocks 中文说明

这是一个用于 Windows 任务栏的额度显示工具，可以快速查看 ChatGPT / Codex 和 Claude 的剩余额度。

本版本基于 [NathanCheng685/quota-blocks](https://github.com/NathanCheng685/quota-blocks) 项目进行修改，主要按照个人电脑的使用习惯和界面偏好进行了调整，包括：

- 将额度信息显示在 Windows 任务栏上；
- 根据剩余额度使用绿色、黄色和红色显示；
- 在 Claude 未安装或不可用时自动隐藏对应行；
- 调整详细面板的字体、图标大小和布局宽度；
- 移除个人不需要的 Codex 重置提醒功能；
- 增加适合当前 Windows 环境的界面截图和使用说明。

## 版权与许可

本项目是基于 NathanCheng685 的原项目进行的个人修改版本。原项目的版权、作者署名和 MIT 许可证仍归原作者 NathanCheng685 所有。

本仓库不主张拥有原项目代码、设计、资源或品牌的版权，也没有改变原项目的许可证要求。使用、复制、修改和再发布时，请继续保留原项目的版权声明和 MIT 许可证内容。

本项目与 OpenAI、ChatGPT、Anthropic 或 Claude 官方没有隶属、赞助或认可关系。相关名称和标志归其各自所有者所有。

## Windows 安装位置

程序默认安装在：

```text
C:\Users\你的用户名\AppData\Local\Programs\QuotaBlocks
```

程序支持 Windows 10/11，并可以通过“开机自动启动”选项随系统启动。

## 当前效果

详细面板：

![Windows 详细面板](windows/docs/panel-zh-current.png)

任务栏显示：

![Windows 任务栏显示](windows/docs/taskbar-current.png)

## 原项目

- 原作者：[NathanCheng685](https://github.com/NathanCheng685)
- 原项目：[NathanCheng685/quota-blocks](https://github.com/NathanCheng685/quota-blocks)
- 许可证：[MIT License](LICENSE)
