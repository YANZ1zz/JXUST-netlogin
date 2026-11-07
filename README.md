# JXUST-netlogin

江西理工大学（JXUST）校园网自动登录助手的分发仓库。

本仓库**只放发布产物**，不放源码：

| 文件 | 用途 |
|---|---|
| `AutoNetHelper-win64.zip` | Windows 64 位程序包（两个 exe + 一键卸载.bat + SHA256SUMS） |
| `update.json` | 客户端自动更新清单（版本号、下载地址、SHA-256、大小） |

两个文件名**固定不变**，客户端固定读取：

```
https://github.com/YANZ1zz/JXUST-netlogin/releases/latest/download/update.json
```

## 给使用者

下载 [最新版本](https://github.com/YANZ1zz/JXUST-netlogin/releases/latest)，解压后双击 `AutoNetHelper.exe`。

首次运行会被 SmartScreen 拦截，点「更多信息 → 仍要运行」。

从 1.5.4 起程序会自动更新，不需要再来这里下载。
1.5.1 ~ 1.5.3 的旧版没有更新器，需要手动替换最后一次。
