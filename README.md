# Huaye Mac Manager · 花爷 Mac 管家

**A lightweight, native Mac cleaner, app uninstaller and duplicate file finder.** 4 MB, Apple Silicon + Intel, macOS 13+, 13 languages.

- **System cleanup** — app caches, developer and AI-app caches, browser data, logs, Trash. About 500 cleanup rules, each with a written reason; keychains, Mail, Messages, Photos, cloud-drive folders, password managers and Xcode simulators are never touched.
- **File cleanup** — large and duplicate files (matched by content), never pre-selected, always moved to the Trash.
- **App uninstaller** — removes apps with their leftovers (strict bundle-ID matching) and their Dock icons.
- **Menu bar panel** — CPU, memory pressure, disk and network at a glance.
- **Private** — no account, no telemetry. Signed and notarized by Apple.

**Download:** [latest release](https://github.com/dotnot2014/mysoftware/releases/latest) · **Website:** [cleanmac.yisihudong.com](https://cleanmac.yisihudong.com/en/) · **Pricing:** free 14-day trial, scanning stays free, one-time license from US$6.99

**Compare & learn:** [CleanMyMac alternative](https://cleanmac.yisihudong.com/en/cleanmymac-alternative/) · [How to completely uninstall apps on Mac](https://cleanmac.yisihudong.com/en/guides/uninstall-apps-on-mac/) · [How to clear System Data](https://cleanmac.yisihudong.com/en/guides/clear-system-data-on-mac/) · [Find duplicate files](https://cleanmac.yisihudong.com/en/guides/find-duplicate-files-on-mac/) · [Is it safe to delete caches?](https://cleanmac.yisihudong.com/en/guides/is-it-safe-to-delete-mac-caches/)

---

## 中文说明

「花爷 Mac 管家」是 macOS 上的本地系统维护工具：**系统清理**、**文件清理**、**应用卸载**、**菜单栏硬件状态面板**。所有数据只留在本机，无账号、无云端同步、无后台上报。支持 13 种界面语言。

官网：<https://cleanmac.yisihudong.com/> · English: <https://cleanmac.yisihudong.com/en/>

> 本仓库**只用于分发安装包**（源码不在此仓库），安装包见下方 Release。

## 下载

**最新版 v2.3.1**（Apple Silicon / Intel 通用）：

- GitHub：[huaye-mac-manager-2.3.1-universal.dmg](https://github.com/dotnot2014/mysoftware/releases/download/v2.3.1/huaye-mac-manager-2.3.1-universal.dmg)
- 国内直链：[cleanmac.yisihudong.com/download/huaye-mac-manager-2.3.1-universal.dmg](https://cleanmac.yisihudong.com/download/huaye-mac-manager-2.3.1-universal.dmg)

更新说明见 [Release 页面](https://github.com/dotnot2014/mysoftware/releases/latest)。本仓库只保留最新版本的安装包。已安装 v2.3.0 及以上的，可以在应用的「设置 › 更新」里直接下载并安装新版本。

## 安装

1. 下载 `.dmg` 并打开，把应用拖进「应用程序」
2. 升级时**先在菜单栏图标里退出旧版**，再覆盖安装；设置、清理日志、注册码与试用期全部保留
3. 安装包使用 Apple Developer ID 签名并通过苹果公证，双击即可打开

## 校验下载完整性

```shell
shasum -a 256 ~/Downloads/huaye-mac-manager-2.3.1-universal.dmg
```

应等于 `f0d1a8ec9d5f57e081cb8463b6fc2a728be129c34036e7ab5f85f2ade9328d7e`。各版本的校验值写在对应 Release 的说明里。

## 系统要求

- macOS 13 及以上
- Apple Silicon 或 Intel

## 试用与购买

- 首次运行自动开始 **14 天全功能试用**
- 试用结束后，菜单栏面板、健康体检、扫描永久免费；执行清理与卸载需要购买
- 在应用里点「购买」，或到 [官网购买页](https://cleanmac.yisihudong.com/buy/)：个人版 1 台 Mac、家庭版 3 台，买断含 v2.x 全部更新；付款后点「在应用中激活」一键激活，注册码离线校验
- 注册码售出后一般不退款，请先用满试用期再购买，详见 [退款政策](https://cleanmac.yisihudong.com/refund/)

## 隐私

应用只在三种情况下联网：你主动测速；每天最多一次检查更新（只下载官网上的版本信息文件，可关闭）；你主动点「下载并安装」时下载新版本。详见 [隐私政策](https://cleanmac.yisihudong.com/privacy/)。

联系：[5168247@qq.com](mailto:5168247@qq.com)
