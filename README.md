# 🔐 S-IT USB-Lock

🇩🇪 [Diese Seite auf Deutsch](README_DE.md)

**Encrypt any external drive once – then unlock and lock it at the push of a button.**

S-IT USB-Lock is a pair of free Windows tools for USB sticks, external SSDs and hard drives. Once set up, the drive can be unlocked and locked on any Windows PC without installing anything – all required files are stored on the drive itself.

The programs are available in German.

---

## The tool pair

| Program | Purpose |
|---|---|
| **S-IT UsbSetup** | One-time setup: partitioning and AES-256 encryption with VeraCrypt |
| **S-IT UsbLock** | Daily use: unlock and lock at the push of a button, up to three drives at the same time |

---

## Features

- 🛡️ AES-256 encryption based on VeraCrypt
- 💻 Portable – UsbLock starts directly from the drive, nothing is installed on the PC
- 🗂️ Up to three S-IT drives unlocked at the same time
- ⚡ Fast setup – about three minutes for a 500 GB hard drive
- ⬇️ VeraCrypt is downloaded in its latest version from the official source during the first setup
- 🔧 Set up a new drive directly from UsbLock

---

## System requirements

- Windows 10 / Windows 11 (64-bit)
- Administrator rights
- USB 3.0 or USB-C recommended
- External drive (at least 2 GB)
- Internet connection once, during the first setup (VeraCrypt download, about 54 MB)

---

## Download

Download the current version from the [releases page](https://github.com/SattlerIT/sit-usblock/releases/latest), unzip it and start `USB-Lock-Setup\S-IT-UsbSetup.exe`.

**Package contents:**
- `S-IT-UsbLock.exe` with help file
- `USB-Lock-Setup\S-IT-UsbSetup.exe` with help file
- `Lizenz.txt`, `Disclaimer.txt`, `CHANGELOG.txt`

Project page: [sattlerit.github.io/sit-usblock](https://sattlerit.github.io/sit-usblock/)

---

## Note on antivirus software

As independently developed software, the programs may be classified as unknown by Windows SmartScreen or security software on first start. All files are published exclusively on this GitHub page. The SHA-256 checksum of the current ZIP file is listed on the project page.

---

## License

S-IT USB-Lock is freeware by Sattler IT-Service, Greifenstein. Free use and redistribution are permitted; commercial reuse or modification without permission is not allowed. See `Lizenz.txt` and `Disclaimer.txt`.

VeraCrypt is an independent open-source project and not part of S-IT USB-Lock. VeraCrypt's own license terms apply (Apache License 2.0 and TrueCrypt License 3.0); the license texts are placed in the `VeraCrypt` folder during setup.

---

## Contact & donation

Contact: tool-entwicklung@sattler-it.de  
Donation: [PayPal](https://www.paypal.com/donate/?business=tool-entwicklung%40sattler-it.de&currency_code=EUR)  
More tools: [sattlerit.github.io/sattlerit-tools](https://sattlerit.github.io/sattlerit-tools/)

© 2026 Sattler IT-Service, Greifenstein · Author: Hans Udo Sattler
