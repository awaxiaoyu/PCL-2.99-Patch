# PCL 2.99.0.0 个人补丁版

本版本由 [awaxiaoyu](https://github.com/awaxiaoyu) 个人制作，与 PCL 官方无关，仅供学习用途。

[下载最新版本](https://github.com/awaxiaoyu/PCL-2.99-Patch/releases/latest)

## 功能

- 在系统设置中提供“解除 MC 下载限制”按钮。
- 点击按钮后显示确认弹窗，说明个人制作、与 PCL 官方无关及学习用途；选择“继续”后解除本次运行的下载限制，选择“取消”则保留限制。
- 下载相关改动覆盖 Minecraft、Mod、整合包、数据包、资源包及光影包，并接入资源详情页的下载入口。
- 屏蔽 PCL 启动器自身的更新检查入口、更新下载启动、更新重启与程序替换。

## 使用

1. 从 [Releases](https://github.com/awaxiaoyu/PCL-2.99-Patch/releases) 下载 `Plain.Craft.Launcher.2.unlimited.exe`。
2. 保留原程序，将补丁版放在原 PCL 所在目录。退出正在运行的 PCL 后，启动补丁版。
3. 打开系统设置，点击“解除 MC 下载限制”，阅读确认弹窗并选择“继续”。

下载解锁状态只在本次进程中有效，重新启动后需要重新确认。PCL 自身更新屏蔽直接写入该补丁版程序，重新启动后仍然有效。

## 文件校验

| 文件 | SHA256 |
| --- | --- |
| 原始 PCL 2.99.0.0 EXE | `6B6E1260CB5A1D6A303855F1C60CAB3D0BC1AEBBA7E40A964180188B271E7386` |
| 本仓库 Release 补丁版 EXE | `883AF0EC069F1986648F98A7DF975CFF6205A94CBB00ACBD37C926EADD0DCEA3` |

Release 附有 `SHA256SUMS.txt`。可在 PowerShell 中核对：

```powershell
Get-FileHash -Algorithm SHA256 -LiteralPath '.\Plain.Craft.Launcher.2.unlimited.exe'
```

基础程序及第三方组件的权利与许可归各自权利人；本项目的个人修改不代表 PCL 官方。
