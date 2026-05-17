# Shadowrocket for Android

**面向 Android 的现代 VPN 客户端，支持代理配置管理、节点测速、路由工具、备份和网络诊断。**

[← All languages](../README.md) · [使用文档](https://docs.shadowrockets.app)

## 最新版本

| Item | Value |
| --- | --- |
| Version | `10.10.5` |
| Channel | `Standard` |
| Release tag | `v10.10.5-standard` |
| Package format | APK |
| Android | Android 7.0+ recommended |

## 下载 APK

请选择与你设备 CPU 架构匹配的 APK。如果不确定，优先下载 arm64-v8a。

| 设备类型 | APK 文件 |
| --- | --- |
| 大多数现代 Android 手机 | [`Shadowrocket_10.10.5_shadowrocketStandard_arm64-v8a.apk`](../releases/download/v10.10.5-standard/Shadowrocket_10.10.5_shadowrocketStandard_arm64-v8a.apk) |
| 较老的 32 位 Android 手机 | [`Shadowrocket_10.10.5_shadowrocketStandard_armeabi-v7a.apk`](../releases/download/v10.10.5-standard/Shadowrocket_10.10.5_shadowrocketStandard_armeabi-v7a.apk) |
| 64 位 Android 模拟器 | [`Shadowrocket_10.10.5_shadowrocketStandard_x86_64.apk`](../releases/download/v10.10.5-standard/Shadowrocket_10.10.5_shadowrocketStandard_x86_64.apk) |
| 较老的 Android 模拟器 | [`Shadowrocket_10.10.5_shadowrocketStandard_x86.apk`](../releases/download/v10.10.5-standard/Shadowrocket_10.10.5_shadowrocketStandard_x86.apk) |

## 功能亮点

- 代理配置管理，支持导入、分享和备份。
- 一键连接和节点延迟测试。
- 节点检测页面，支持浏览器访问检测和 DNS 建议。
- 策略组和代理链，适合高级路由场景。
- 支持 Hysteria2、Xray TUN、本地 DNS、FakeDNS 和自定义 VPN DNS。
- 支持 WebDAV 备份与恢复，方便迁移配置。
- 支持应用内订阅解锁高级功能。

## 安装步骤

1. 从最新 GitHub Release 下载 APK。
2. 在 Android 设备上打开 APK。
3. 如果系统阻止安装，请允许浏览器或文件管理器安装未知来源应用。
4. 打开 Shadowrocket，并按提示授予 VPN 权限。
5. 导入或添加代理配置，然后点击连接。

## 常见问题

**为什么安装 APK 前 Android 会提示风险？**  
只要应用不是从 Google Play 安装，Android 通常都会提示。请只从这个官方仓库下载。

**我应该安装哪个 APK？**  
大多数手机选择 arm64-v8a；只有较老的 32 位设备才选择 armeabi-v7a。

**为什么节点显示已连接，但某些网站仍打不开？**  
部分节点或网络需要不同的 DNS 处理方式。可以使用应用内节点检测，并根据建议开启本地 DNS/FakeDNS 或修改 VPN DNS。

**发布新版本后需要卸载重装吗？**  
通常直接覆盖安装新版 APK 即可，应用数据会保留。
