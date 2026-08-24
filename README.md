# 破甲高手 (PojiaGaoshou)

破甲高手 · 公开安装包下载。

> 源码私有，本仓库仅分发安装包。
>
> 作者 QQ：**2537420218**

## 下载 v1.2.0

| 平台 | 架构 | 文件 | 下载 |
| --- | --- | --- | --- |
| Windows | x64 | `PojiaGaoshou-1.2.0-win-x64.exe` | [下载](https://github.com/yanstu/pojia-gaoshou-releases/releases/download/v1.2.0/PojiaGaoshou-1.2.0-win-x64.exe) |
| Linux | x64 | `PojiaGaoshou-1.2.0-linux-x64.AppImage` | [下载](https://github.com/yanstu/pojia-gaoshou-releases/releases/download/v1.2.0/PojiaGaoshou-1.2.0-linux-x64.AppImage) |
| macOS (Intel) | x64 | `PojiaGaoshou-1.2.0-mac-x64.zip` | [下载](https://github.com/yanstu/pojia-gaoshou-releases/releases/download/v1.2.0/PojiaGaoshou-1.2.0-mac-x64.zip) |
| macOS (Apple Silicon) | arm64 | `PojiaGaoshou-1.2.0-mac-arm64.zip` | [下载](https://github.com/yanstu/pojia-gaoshou-releases/releases/download/v1.2.0/PojiaGaoshou-1.2.0-mac-arm64.zip) |

全部版本见 [Releases 页面](https://github.com/yanstu/pojia-gaoshou-releases/releases)。

## SHA256 校验

```text
26fc06f4cc883c1f91aaa5c6f9f964a239a97ba501c5a6ecb79b52290da71fce  PojiaGaoshou-1.2.0-win-x64.exe
3d5515b41f89f14a9423034a836c9592e5b398c9365a281e800be3b553261ab4  PojiaGaoshou-1.2.0-linux-x64.AppImage
e769d8a1e2017d85824ba8893671f22aa21bf732898e07f6a882176838b8443c  PojiaGaoshou-1.2.0-mac-x64.zip
9c64acf4abeb6ef0283597c3ef56e618bf8765a87923caf9da38ed48c002b283  PojiaGaoshou-1.2.0-mac-arm64.zip
```

校验方法：

```bash
sha256sum -c SHA256SUMS.txt        # Linux
shasum -a 256 -c SHA256SUMS.txt    # macOS
CertUtil -hashfile PojiaGaoshou-1.2.0-win-x64.exe SHA256   # Windows
```

## 说明

- macOS 包为未签名的 `.app` 压缩包，首次打开需在「系统设置 → 隐私与安全性」中允许运行。
- Linux AppImage 需先 `chmod +x` 再运行。
