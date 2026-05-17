# Shadowrocket for Android

**適用於 Android 的現代 VPN 用戶端，支援代理設定管理、節點測速、路由工具、備份與網路診斷。**

[← All languages](../README.md) · [使用文件](https://docs.shadowrockets.app)

## 最新版本

| Item | Value |
| --- | --- |
| Version | `10.10.5` |
| Channel | `Standard` |
| Release tag | `v10.10.5-standard` |
| Package format | APK |
| Android | Android 7.0+ recommended |

## 下載 APK

請選擇符合裝置 CPU 架構的 APK。如果不確定，建議優先下載 arm64-v8a。

| 裝置類型 | APK 檔案 |
| --- | --- |
| 大多數現代 Android 手機 | [`Shadowrocket_10.10.5_shadowrocketStandard_arm64-v8a.apk`](../releases/download/v10.10.5-standard/Shadowrocket_10.10.5_shadowrocketStandard_arm64-v8a.apk) |
| 較舊的 32 位元 Android 手機 | [`Shadowrocket_10.10.5_shadowrocketStandard_armeabi-v7a.apk`](../releases/download/v10.10.5-standard/Shadowrocket_10.10.5_shadowrocketStandard_armeabi-v7a.apk) |
| 64 位元 Android 模擬器 | [`Shadowrocket_10.10.5_shadowrocketStandard_x86_64.apk`](../releases/download/v10.10.5-standard/Shadowrocket_10.10.5_shadowrocketStandard_x86_64.apk) |
| 較舊的 Android 模擬器 | [`Shadowrocket_10.10.5_shadowrocketStandard_x86.apk`](../releases/download/v10.10.5-standard/Shadowrocket_10.10.5_shadowrocketStandard_x86.apk) |

## 功能亮點

- 代理設定管理，支援匯入、分享與備份。
- 一鍵連線與節點延遲測試。
- 節點檢測頁面，支援瀏覽器存取檢測與 DNS 建議。
- 策略組與代理鏈，適合進階路由情境。
- 支援 Hysteria2、Xray TUN、本機 DNS、FakeDNS 與自訂 VPN DNS。
- 支援 WebDAV 備份與還原，方便移轉設定。
- 支援應用程式內訂閱解鎖進階功能。

## 安裝步驟

1. 從最新 GitHub Release 下載 APK。
2. 在 Android 裝置上開啟 APK。
3. 如果系統阻擋安裝，請允許瀏覽器或檔案管理器安裝未知來源應用程式。
4. 開啟 Shadowrocket，並依提示授予 VPN 權限。
5. 匯入或新增代理設定，然後點選連線。

## 常見問題

**為什麼安裝 APK 前 Android 會顯示警告？**  
只要應用程式不是從 Google Play 安裝，Android 通常都會顯示提示。請只從此官方倉庫下載。

**我應該安裝哪個 APK？**  
大多數手機選擇 arm64-v8a；只有較舊的 32 位元裝置才選擇 armeabi-v7a。

**為什麼節點已連線，但部分網站仍無法開啟？**  
部分節點或網路需要不同 DNS 處理方式。可使用應用程式內節點檢測，並依建議開啟本機 DNS/FakeDNS 或修改 VPN DNS。

**發布新版本後需要卸載重裝嗎？**  
通常直接覆蓋安裝新版 APK 即可，應用程式資料會保留。
