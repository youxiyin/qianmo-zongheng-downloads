# 阡陌纵横 · 安卓 APK 发布渠道

本仓只存放经过构建验收的 APK 与校验值（Releases）。源码在开发仓 [youxiyin/qianmo-zongheng](https://github.com/youxiyin/qianmo-zongheng)（private）。

## 下载

- 最新：[v1.1.0 qianmo-zongheng.apk](https://github.com/youxiyin/qianmo-zongheng-downloads/releases/download/v1.1.0/qianmo-zongheng.apk)
- 校验：各 Release 附 `SHA256SUMS.txt` 与 `BUILD.json`（来源 commit/版本）。
- 扫码：开发仓 audits 内 `qr-github-release.png` 编码上述直链；跨网/流量可直接扫（GitHub Releases 公开匿名可下）。

## 安装

1. 下载 apk → 打开 → 允许「安装未知应用」→ 安装（覆盖安装保留存档）。
2. 打开即横屏；单机离线本地结算，无需服务器。
3. 校验：`sha256sum -c SHA256SUMS.txt`。

## 版本

- v1.1.0（versionCode 2）：单机横屏；地图主体/控件贴边/隐藏小地图；debug 包。
- 发布流程：开发仓 tag `v*` → CI 构建 → 自动发布到本仓（需开发仓 secret RELEASES_TOKEN）。

真机体验验收独立于构建验收；未签不代签。
