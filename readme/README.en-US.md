# Shadowrocket for Android

**Fast, modern VPN client for Android with proxy profile management, node testing, routing tools, backup, and network diagnosis.**

[← All languages](../README.md) · [Documentation](https://docs.shadowrockets.app)

## Latest Release

| Item | Value |
| --- | --- |
| Version | `10.10.5` |
| Channel | `Standard` |
| Release tag | `v10.10.5-standard` |
| Package format | APK |
| Android | Android 7.0+ recommended |

## Download APK

Choose the APK that matches your device architecture. If you are not sure, download arm64-v8a first.

| Device type | APK file |
| --- | --- |
| Most modern Android phones | [`Shadowrocket_10.10.5_shadowrocketStandard_arm64-v8a.apk`](https://github.com/Pawdroid/shadowrocket_for_android/releases/download/v10.10.5-standard/Shadowrocket_10.10.5_shadowrocketStandard_arm64-v8a.apk) |
| Older 32-bit Android phones | [`Shadowrocket_10.10.5_shadowrocketStandard_armeabi-v7a.apk`](https://github.com/Pawdroid/shadowrocket_for_android/releases/download/v10.10.5-standard/Shadowrocket_10.10.5_shadowrocketStandard_armeabi-v7a.apk) |
| 64-bit Android emulator | [`Shadowrocket_10.10.5_shadowrocketStandard_x86_64.apk`](https://github.com/Pawdroid/shadowrocket_for_android/releases/download/v10.10.5-standard/Shadowrocket_10.10.5_shadowrocketStandard_x86_64.apk) |
| Older Android emulator | [`Shadowrocket_10.10.5_shadowrocketStandard_x86.apk`](https://github.com/Pawdroid/shadowrocket_for_android/releases/download/v10.10.5-standard/Shadowrocket_10.10.5_shadowrocketStandard_x86.apk) |

## Highlights

- Proxy profile management with import, share, and backup tools.
- One-tap connection and node latency testing.
- Node diagnosis with browser-based access checks and DNS suggestions.
- Policy groups and proxy chains for advanced routing scenarios.
- Hysteria2, Xray TUN, local DNS, FakeDNS, and configurable VPN DNS.
- WebDAV backup and restore for configuration portability.
- In-app subscription support for premium features.

## Install

1. Download the APK from the latest GitHub Release.
2. Open the APK on your Android device.
3. If Android blocks the installation, allow installation from your browser or file manager.
4. Open Shadowrocket and grant VPN permission when prompted.
5. Import or add your proxy profile, then tap Connect.

## FAQ

**Why does Android warn me before installing the APK?**  
Android shows this warning for apps installed outside Google Play. Download only from this official repository.

**Which APK should I install?**  
Use arm64-v8a for most phones. Use armeabi-v7a only for older 32-bit devices.

**Why can a node connect but some websites still fail?**  
Some nodes or networks need different DNS handling. Try the in-app node diagnosis page, then follow its suggestions such as enabling local DNS/FakeDNS or changing VPN DNS.

**Do I need to reinstall when a new version is released?**  
You can install the new APK over the old version. Your app data is normally preserved.
