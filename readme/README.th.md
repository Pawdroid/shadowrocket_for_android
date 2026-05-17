# Shadowrocket for Android

**ไคลเอนต์ VPN สมัยใหม่สำหรับ Android พร้อมการจัดการพร็อกซี ทดสอบโหนด การกำหนดเส้นทาง สำรองข้อมูล และวิเคราะห์เครือข่าย**

[← All languages](../README.md) · [เอกสาร](https://docs.shadowrockets.app)

## รุ่นล่าสุด

| Item | Value |
| --- | --- |
| Version | `10.10.5` |
| Channel | `Standard` |
| Release tag | `v10.10.5-standard` |
| Package format | APK |
| Android | Android 7.0+ recommended |

## ดาวน์โหลด APK

เลือก APK ให้ตรงกับสถาปัตยกรรม CPU ของอุปกรณ์ หากไม่แน่ใจ ให้เลือก arm64-v8a ก่อน

| ประเภทอุปกรณ์ | APK |
| --- | --- |
| โทรศัพท์ Android รุ่นใหม่ส่วนใหญ่ | [`Shadowrocket_10.10.5_shadowrocketStandard_arm64-v8a.apk`](../releases/download/v10.10.5-standard/Shadowrocket_10.10.5_shadowrocketStandard_arm64-v8a.apk) |
| โทรศัพท์ Android 32-bit รุ่นเก่า | [`Shadowrocket_10.10.5_shadowrocketStandard_armeabi-v7a.apk`](../releases/download/v10.10.5-standard/Shadowrocket_10.10.5_shadowrocketStandard_armeabi-v7a.apk) |
| Android emulator 64-bit | [`Shadowrocket_10.10.5_shadowrocketStandard_x86_64.apk`](../releases/download/v10.10.5-standard/Shadowrocket_10.10.5_shadowrocketStandard_x86_64.apk) |
| Android emulator รุ่นเก่า | [`Shadowrocket_10.10.5_shadowrocketStandard_x86.apk`](../releases/download/v10.10.5-standard/Shadowrocket_10.10.5_shadowrocketStandard_x86.apk) |

## คุณสมบัติเด่น

รองรับการนำเข้า แชร์ และสำรองโปรไฟล์พร็อกซี เชื่อมต่อในครั้งเดียว ทดสอบ latency ตรวจสอบโหนดผ่านเบราว์เซอร์ แนะนำ DNS/FakeDNS กลุ่มนโยบาย proxy chain และสำรองผ่าน WebDAV

## การติดตั้ง

ดาวน์โหลด APK จาก GitHub Releases แล้วเปิดบนอุปกรณ์ Android หากระบบบล็อกการติดตั้ง ให้อนุญาตการติดตั้งจากเบราว์เซอร์หรือตัวจัดการไฟล์ เปิดแอป อนุญาตสิทธิ์ VPN แล้วนำเข้าหรือเพิ่มโปรไฟล์

## คำถามที่พบบ่อย

โทรศัพท์ส่วนใหญ่ใช้ arm64-v8a ได้ ใช้ armeabi-v7a เฉพาะอุปกรณ์ 32-bit รุ่นเก่า หากเชื่อมต่อแล้วบางเว็บยังเปิดไม่ได้ ให้ใช้หน้าตรวจสอบโหนด แล้วลองเปิด DNS ภายใน/FakeDNS หรือเปลี่ยน VPN DNS สามารถติดตั้ง APK ใหม่ทับเวอร์ชันเดิมได้
