# 🔐 S-IT USB-Lock

**Portable USB encryption tools for Windows using VeraCrypt**

Beliebige USB-Datenträger (SSD, HDD, USB-Stick) einmalig verschlüsseln — danach per Knopfdruck **Entsperren** und **Sperren**. Kein separates Installationsmedium, keine Installation auf dem Gast-PC notwendig.

---

## Das Tool-Paar

| Komponente | Zweck |
|---|---|
| **S-IT-UsbSetup.exe** | Einmalige Einrichtung: Partitionierung + AES-256-Verschlüsselung |
| **S-IT-UsbLock.exe** | Täglicher Einsatz: Entsperren und Sperren auf Knopfdruck |

---

## Funktionen

- 🛡️ AES-256-Verschlüsselung via VeraCrypt (portabel, im Paket enthalten)
- 💻 Portabel – UsbLock startet direkt vom Datenträger, keine PC-Installation nötig
- ⚡ Schnelle Einrichtung dank VeraCrypt `/quick /FastCreateFile` – auch große Datenträger in wenigen Minuten
- 🔍 Automatische Erkennung des S-IT-Datenträgers beim Start
- 🔧 Neuen Datenträger direkt aus UsbLock einrichten (startet UsbSetup vom Gerät)
- 📋 Vollständiges Log bei der Einrichtung

---

## Systemanforderungen

- Windows 10 / Windows 11 (64-Bit)
- Administratorrechte
- USB 3.0 oder USB-C empfohlen
- Externer Datenträger (mind. 2 GB)

---

## Download

Aktuelle Version im [Release-Bereich](https://github.com/SattlerIT/sit-usblock/releases/latest) herunterladen, entpacken und starten.

**Lieferumfang:**
- `S-IT-UsbLock.exe`
- `S-IT-UsbSetup.exe`
- Hilfe-Dateien (HTML)
- `S-IT-USB-Lock-Anleitung.pdf`
- VeraCrypt (portabel, inkl. Lizenzen)

---

## Hinweis zu Virenscannern

Da es sich um unabhängig entwickelte Software handelt, kann Windows SmartScreen die Datei beim ersten Start als unbekannt einstufen. Bitte als vertrauenswürdig bestätigen. Alle Dateien stammen ausschließlich von dieser GitHub-Seite.

---

## Lizenz

S-IT USB-Lock ist Freeware von Sattler IT-Service, Greifenstein.  
Enthält VeraCrypt (Apache 2.0 / TrueCrypt 3.0 Lizenz) — vollständige Lizenztexte im `VeraCrypt\`-Unterordner.

---

## Kontakt & Spende

Fragen: kontakt@sattler-it.de  
Spende: [PayPal](https://www.paypal.com/donate/?business=tool-entwicklung%40sattler-it.de&currency_code=EUR)  
Weitere Tools: [sattlerit.github.io/sattlerit-tools](https://sattlerit.github.io/sattlerit-tools/)

© 2026 Hans Udo Sattler · Sattler IT-Service, Greifenstein
