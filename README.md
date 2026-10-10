# Aseprite 中文清晰字体主题

一套基于 Aseprite 官方默认主题制作的中文字体主题，包含浅色和深色两种配色。

## 特性

- 英文界面保留 Aseprite 原生像素字体。
- 中文界面启用抗锯齿字体回退，改善高分辨率屏幕上的可读性。
- Windows 使用微软雅黑，macOS 使用苹方，Linux 使用思源黑体。
- 悬停提示框使用独立的中文字体度量，使背景尺寸与实际文字一致。
- 同时提供浅色 `cn-clear` 和深色 `cn-clear-dark` 主题。

## 安装

1. 从 Releases 下载 `aseprite-theme-cn-1.2.0.aseprite-extension`。
2. 在 Aseprite 中打开“编辑 > 首选项 > 扩展”。
3. 点击“添加扩展”，选择下载的文件。
4. 在“编辑 > 首选项 > 主题”中选择 `cn-clear` 或 `cn-clear-dark`。
5. 重新启动 Aseprite，使字体资源完整加载。

也可以将仓库内容复制到 Aseprite 的扩展目录。便携版通常位于程序目录下的 `extensions` 或 `data/extensions`。

## 兼容性

当前主题基于 Aseprite 1.3.18 系列的默认主题资源制作。其他 1.3.x 版本通常也可以使用，但新增控件可能沿用默认主题样式。

## 字体

主题不会分发操作系统字体，而是按平台加载下列字体：

- Windows: `msyh.ttc`
- macOS: `PingFang.ttc`
- Linux: `NotoSansCJK-Regular.ttc`

## 许可

主题资源基于 Aseprite Default Theme，并依照 [Creative Commons Attribution 4.0](LICENSE.txt) 许可发布。
