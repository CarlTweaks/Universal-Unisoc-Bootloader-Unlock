# 🚀 Universal Unisoc Bootloader Unlocker (WebUSB Edition)

A mobile-first, browser-based tool to bypass signature verification and unlock the bootloader of Unisoc (Spreadtrum) devices. No PC, no Root, just pure WebUSB power.

## 🌟 Features
- **No PC Required**: Works entirely in your Android Chrome browser.
- **Hybrid Protocol**: Supports latest security patches (including v1964/2025) by using older Stock FDLs.
- **Universal Support**: Compatible with UFS 2.2 and eMMC storage (T606, T612, ums9230, etc.).

---

## 🛠️ Requirements
1. **Host Phone**: Android device with Chrome browser.
2. **OTG Adapter**: To connect the Host to the Target phone.
3. **Chrome Configuration**:
   - Go to `chrome://flags`
   - Enable `#enable-unrestricted-usb`
   - Enable `#automatic-usb-detach`
   - Relaunch Chrome.

---

## 📂 Preparation
To use this tool, you need three binary files:
1. **Stock FDL1**: Extract from your phone's official firmware (.pac file).
2. **Signature Bypass (Included)**: Download the `universal_bypass.bin` from this repository.
3. **Stock FDL2**: Extract from your phone's official firmware (ensure it matches your storage type: UFS or eMMC).

---

## ⚡ How to Use (The Gar Protocol)
1. Open the [Gar-Unlocker Link](https://YOUR-USERNAME.github.io/Universal-Unisoc-Bootloader-Unlock/).
2. Select your **Stock FDL1**, the **Bypass Bin**, and your **Stock FDL2**.
3. Click **"EXECUTE HANDSHAKE"**.
4. **Target Phone Action**:
   - Power OFF the device.
   - Press and hold **Volume Down or volume up + volume down** depends on your device.
   - Plug the OTG cable into the Target phone.
5. In the Chrome popup, select **"Spreadtrum/Unisoc"** and click **Connect**.
6. Wait for the log to show `✅ PROTOCOL COMPLETE`.

---

## ⚠️ Disclaimer
*Usage of this tool may void your warranty, wipe your data, or brick your device. Use at your own risk. This project is for educational purposes only.*

## 🤝 Credits
- **Exploit & Payload**: TomKing062
- **Logic & Implementation**: (CarlTweaks)
- **Web Interface**: Based on WebUSB API
