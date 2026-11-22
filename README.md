# Weavra 下载与更新

此仓库仅用于分发 Weavra 桌面安装包、更新文件与校验值，不存放应用项目源码。

## 下载

[打开最新版本](https://github.com/liuwqq/Weavra-releases/releases/latest)

Windows x64（Intel / AMD）请选择 `weavra-1.0.15-Setup.exe`。安装前退出旧版本，并备份本地数据与项目目录。安装器可能联网准备 Bun 与 WebView2 运行时。本次发布的安装包未进行 Windows 代码签名，可用随版本提供的 SHA-256 文件核对下载。

## 自动更新源

```text
https://github.com/liuwqq/Weavra-releases/releases/latest/download
```

新安装包已默认使用此地址，无需 GitHub 账号或令牌即可读取更新文件。网络仍需能够访问 GitHub；必要时使用自己的网络代理。

旧安装包若仍连接私有仓库，请下载这里的新包并覆盖安装一次。也可在支持自定义更新源的客户端中填写上面的地址，再选择自定义源检查更新。已有自定义源不会被新包强行覆盖。

| 附件 | 用途 |
| --- | --- |
| `weavra-1.0.15-Setup.exe` | Windows x64 手动安装。 |
| `stable-win-x64-update.json` | 客户端更新清单。 |
| `stable-win-x64-weavra.tar.zst` | 客户端完整更新包。 |
| `SHA256SUMS.txt` | 文件完整性校验。 |

GitHub 自动生成的 “Source code” 压缩包仅包含本分发仓库的说明文件，不是 Weavra 应用源码，也不是安装包。

## 反馈与归属

使用问题可在本仓库提交 Issue。请注明应用版本和复现步骤，并去除账号、密钥及个人素材。

Weavra 基于 Toonflow-app 定制开发；应用随附上游版权和许可证，第三方组件、插件与素材遵循各自许可。此仓库不包含个人账号配置、访问令牌或创作数据。
