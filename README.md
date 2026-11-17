# MacToolBox

macOS 菜单栏工具箱，提供滚动控制、鼠标侧键、Finder 右键增强和设备管理。

## 下载与安装

前往 [最新版本](https://github.com/jronald1024/MacToolBox-Releases/releases/latest)，在 Assets 中下载适合架构的 `.dmg`，打开后将 MacToolBox 拖入“应用程序”。最低系统版本为 macOS 13.5；`arm64` 适用于 Apple 芯片 Mac。只下载版本明确提供的架构安装包。

App 使用 Developer ID 签名并完成 Apple 公证。首次打开后在菜单栏进入工具箱；按需要启用模块及系统权限。

## 应用内更新

0.1.40 起自动优先从 GitHub 检查和下载更新，失败时尝试本机配置的 OneDrive 发布目录。清单及更新包均验证签名、架构、大小与哈希，安装由用户主动确认。

设置页更多菜单提供“查看更新日志”，可查看尝试顺序、失败原因和实际使用的来源。旧版本可先通过 DMG 安装新版，或在 OneDrive 已同步的发布目录中更新。

本仓库只分发安装包、版本说明与签名更新清单，保留最新 10 个正式版本。GitHub 自动生成的 Source code 压缩包不是 App 安装包。GitHub 下载速度取决于当前网络。
