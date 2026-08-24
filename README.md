# 破甲高手 (PojiaGaoshou)

破甲高手 · 公开安装包下载。

> 源码私有，本仓库仅分发安装包。
>
> 作者 QQ：**2537420218**

## 下载 v1.2.2（最新）

| 平台 | 架构 | 文件 | 下载 |
| --- | --- | --- | --- |
| Windows | x64 | `PojiaGaoshou-1.2.2-win-x64.exe` | [下载](https://github.com/yanstu/pojia-gaoshou-releases/releases/download/v1.2.2/PojiaGaoshou-1.2.2-win-x64.exe) |
| Linux | x64 | `PojiaGaoshou-1.2.2-linux-x64.AppImage` | [下载](https://github.com/yanstu/pojia-gaoshou-releases/releases/download/v1.2.2/PojiaGaoshou-1.2.2-linux-x64.AppImage) |
| macOS (Intel) | x64 | `PojiaGaoshou-1.2.2-mac-x64.zip` | [下载](https://github.com/yanstu/pojia-gaoshou-releases/releases/download/v1.2.2/PojiaGaoshou-1.2.2-mac-x64.zip) |
| macOS (Apple Silicon) | arm64 | `PojiaGaoshou-1.2.2-mac-arm64.zip` | [下载](https://github.com/yanstu/pojia-gaoshou-releases/releases/download/v1.2.2/PojiaGaoshou-1.2.2-mac-arm64.zip) |

历史版本见 [Releases 页面](https://github.com/yanstu/pojia-gaoshou-releases/releases)（含 v1.2.1、v1.2.0）。

## SHA256 校验（v1.2.2）

```text
8eeef15da24acba2b9cba1fcfe884201934404abe45c231979f7ec223c56305f  PojiaGaoshou-1.2.2-win-x64.exe
d33e216afc825837257e01d1b5a34df8d8a95bab0b98cd381a178015e13e07f7  PojiaGaoshou-1.2.2-linux-x64.AppImage
6e7b69b06c437c7ada94398a721658e27f0e7927e2d013d29a9743b6ba2bf7b2  PojiaGaoshou-1.2.2-mac-x64.zip
38c353416922a417ef3e2302119b09dc38d14eb850dd45faea4f5da0aefbd8c5  PojiaGaoshou-1.2.2-mac-arm64.zip
```

各版本完整校验和见对应 Release 附带的 `SHA256SUMS.txt`。

校验方法：

```bash
sha256sum -c SHA256SUMS.txt        # Linux
shasum -a 256 -c SHA256SUMS.txt    # macOS
CertUtil -hashfile PojiaGaoshou-1.2.2-win-x64.exe SHA256   # Windows
```

## 说明

- macOS 包为未签名的 `.app` 压缩包，首次打开需在「系统设置 → 隐私与安全性」中允许运行。
- Linux AppImage 需先 `chmod +x` 再运行。
