# EFI for HP devices

[![macOS](https://img.shields.io/badge/macOS-15-blue?style=flat-square&logo=apple)](#)
[![OpenCore](https://img.shields.io/badge/OpenCore-1.0.4-purple?style=flat-square&logo=hackaday)](https://dortania.github.io/OpenCore-Install-Guide/)
[![Status](https://img.shields.io/badge/Status-Working-brightgreen?style=flat-square)](#)
[![License](https://img.shields.io/github/license/DanielvG-IT/HP-EB830-G5-macOS?style=flat-square)](./LICENSE)

> 💻 Clean and stable OpenCore EFI's for running macOS Sequoia.

---

## ✨ Features

✅ iGPU Acceleration\
✅ Sleep, Audio, USB Mapping\
✅ Wi-Fi, Bluetooth (if compatible hardware)\
✅ Clean & Maintainable config.plist

---

## 🧠 BIOS Settings

Please reset your BIOS to defaults and apply the following:

| Setting                 | Value         |
|-------------------------|---------------|
| Legacy Boot             | Disabled      |
| Secure Boot             | Disabled      |
| VT-x          | Enabled       |
| TPM / PTT               | Disabled      |
| Fast Boot               | Disabled      |
| Thunderbolt Assist      | Disabled      |
| Wake on LAN             | Disabled      |
| USB Ports               | Enabled       |
| Battery Fast Charge     | Disabled      |

➡️ Press F10 to save and reboot after setting BIOS.

---

## 🛠 Tools Used

- 🧰 OpenCore Simplify Configurator:  
  https://github.com/samuel-p/openoc-config-simplify

- 🍎 OpenCore macrecovery.py:  
  ```bash
  python macrecovery.py -b Mac-937A206F2EE63C01 -m 00000000000000000 download
  ```

- 🧰 GenSMBIOS:
  https://github.com/corpnewt/GenSMBIOS

---

## 🚧 Known Issues
- HDMI Audio not tested
- Battery percentage sometimes misreported
- Fingerprint scanner doens't work
- Smart card reader doen't work

---

## 📜 License
This repo is licensed under the MIT License. See [LICENSE](LICENSE) for more.

## 🤝 Credits
- Dortania's OpenCore Guide
- CorpNewt's Tooling
- Hackintosh Community on Reddit & InsanelyMac
- You, for giving this project a try ❤️

⭐️ Star this repo if it helped you!
