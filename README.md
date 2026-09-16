# 黑粉录屏 HyphenScreen · 下载

黑粉科技的桌面录屏与智能剪辑软件。本仓库只存放安装包、校验和与发行说明；源码在独立的私有仓库。

**当前版本：[黑粉录屏 0.4.16 · 预览版](https://github.com/HackerChi-Hub/HyphenScreen-Releases/releases/tag/v0.4.16)**（预览版：功能可用，仍在实测中；只保留最新一版）。

## 下载

到[发行页面](https://github.com/HackerChi-Hub/HyphenScreen-Releases/releases/latest)按平台取包。

| 平台 | 文件 | SHA-256 |
|---|---|---|
| macOS 13+（Apple 芯片 arm64） | `HyphenScreen_0.4.16_arm64.dmg` | `79197aca24c2b27027de453aed71fef429b0f0b15d2c1e61cee77495a1fb14d5` |
| Windows 10/11（x64） | `HyphenScreen_0.4.16_x64-setup.exe` | `0ba9598a74d442624c324af134a6f3c748d65d6baeaf31873aff017ab1da5ecd` |
| Linux（x86_64） | `HyphenScreen_0.4.16_x86_64.AppImage` | `de33638c1d04bd833d409a09192cd17bf1c145162788670915ada2cd233b1a21` |
| Debian / Ubuntu（amd64） | `HyphenScreen_0.4.16_amd64.deb` | `a1bffbaaba57e61f7d5eee3ad787f34be3358b77e600a8f219324e4a565e7017` |
| Arch Linux（x86_64） | `HyphenScreen_0.4.16_x64.pacman` | `22304dbe5ab8cbb8444e239086de279382c56151a425a194f960ab5f7f148376` |

同一页附带各平台的 `SHA256SUMS*.txt` 与 `release-manifest.json`，可核对文件完整性与构建来源。

## 安装

- **macOS（Apple 芯片）**：打开 DMG，把「黑粉录屏 HyphenScreen.app」拖进「应用程序」。安装包用黑粉科技本机证书签名、**没有做苹果公证**，首次打开会被拦下：在「应用程序」里右键点图标选「打开」，或先执行
  ```bash
  xattr -dr com.apple.quarantine "/Applications/黑粉录屏 HyphenScreen.app"
  ```
- **Windows 10/11 x64**：运行安装程序，可自选安装目录。**未做代码签名**，SmartScreen 会提示，点「更多信息 → 仍要运行」。
- **Linux x64**：AppImage 需要 FUSE 2（Arch `fuse2`、Debian/Ubuntu `libfuse2`），`chmod +x` 后直接运行；deb 与 pacman 已声明依赖（Vulkan 驱动、`xdg-desktop-portal` 及桌面对应后端、ALSA、libgomp）。基线为 glibc 2.35。

录屏需要系统授权：macOS 在「系统设置 → 隐私与安全性 → 屏幕录制」里勾选；Linux 的录屏全部经 xdg-desktop-portal，需要装上桌面对应的后端（`-gnome`、`-kde`、`-wlr` 等）。

## 说明

- 人声隔离、自动打码的敏感信息识别、框选时「单击窗口取范围」目前只有 macOS 版有，其余功能三平台一致。
- 应用内没有自动更新：新版本发到本页，旧版本会被删除。
- 正式安装版每天最多发送一次匿名使用统计（设备匿名编号、版本、系统、架构），可在编辑器左上角「黑粉录屏」菜单或托盘菜单一键关闭，详见发行说明。

版权所有 © 2026 黑粉科技。基于 MIT 许可的 OpenScreen 开发，第三方许可证随安装包附带。
