# reBar

reBar（原 Remocode Bar）正式安装包公开下载仓库。  
Public download repository for official reBar builds (formerly Remocode Bar).

## 下载 / Download

[下载 macOS Apple Silicon（arm64）](https://github.com/BlueOriginAI/reBar-releases/releases/latest/download/reBar-v2.10.21-macos-arm64.dmg) / [Download Apple Silicon (arm64)](https://github.com/BlueOriginAI/reBar-releases/releases/latest/download/reBar-v2.10.21-macos-arm64.dmg)

从 v2.10.15 起，新版只提供 Apple Silicon arm64 安装包。Intel 与 Universal 历史版本仍可在旧 Release 中下载。
Starting with v2.10.15, new releases provide Apple Silicon arm64 installers only. Historical Intel and Universal packages remain available in previous releases.

## 应用名称 / Application name

从 v2.10.21 起，正式版应用为 `/Applications/reBar.app`。旧路径升级后请接受应用内“迁移并重启”提示，以更新启动器中的实际名称；选择稍后不会删除账号数据。若目标位置已有应用，迁移会停止而非覆盖。
From v2.10.21, the production app is installed at `/Applications/reBar.app`. After updating a legacy installation, accept the migration-and-restart prompt to update the actual launcher name. Deferring preserves account data; migration stops rather than overwriting an occupied destination.

## 自动更新 / Automatic updates

正式版发现新版本后，可在更新弹窗中点击安装，应用会自动下载、校验签名、安装并重启。v2.9.1 及更早版本请先手动安装与设备架构匹配的安装包。
When a new version is available, click Install in the update dialog to download, verify, install, and restart automatically. Users on v2.9.1 or earlier should first install the latest architecture-specific DMG for their Mac.

## 支付环境 / Billing environment

这里发布的正式包固定使用 Stripe 正式环境，提交订阅会产生真实扣款。  
Builds published here use Stripe Live mode. Completing checkout creates a real paid subscription.

## 当前平台 / Current platform

- 新版 macOS Apple Silicon（arm64）；Intel 与 Universal 请使用历史版本。

## 签名说明 / Signing notice

当前新版本使用 Developer ID Application 签名，DMG 经过 Apple 公证并附带公证票据；Updater 更新包另有独立签名，用于校验更新完整性。旧版内部/ad-hoc 安装包保持历史状态。

Current releases use Developer ID Application signing and Apple-notarized DMGs with stapled tickets. Updater archives carry a separate integrity signature. Historical ad-hoc releases remain unchanged.

源代码在私有仓库中维护，本仓库仅用于发布正式安装包与更新元数据。  
Source is maintained privately; this repository distributes official binaries and updater metadata only.

## GPTweb 下线 / GPTweb retirement

从 v2.10.17 起，Bar 移除 GPTweb、浏览器扩展、内置网页模型运行时和相关 MCP 后端，恢复原生界面。账号与额度管理、订阅、正常 API 代理和 Anthropic 兼容接口保留。旧版网页模型客户端请选择 API 模型。

Starting with v2.10.17, Bar removes GPTweb, its browser extension/runtime and Web MCP backend, and restores the native interface. Account/quota management, subscriptions, the normal API proxy and Anthropic compatibility remain. Clients using retired Web models should select an API model.

已有浏览器资料、登录会话、密钥、Tunnel 和云端连接不会自动删除或撤销；这些资源仍由用户管理。
Existing browser data, login sessions, credentials, Tunnels and cloud connections remain under user control.

[历史隐私说明 / Historical privacy notice](https://remocode.cc/products/remocode-bar/privacy) · [支持 / Support](https://remocode.cc/products/remocode-bar/support)
