# 🔐 S-IT USB-Lock

🇬🇧 [This page in English](README.md)

**Beliebige externe Datenträger einmalig verschlüsseln – danach per Knopfdruck entsperren und sperren.**

S-IT USB-Lock ist ein kostenloses Tool-Paar für Windows, für USB-Sticks, externe SSDs und Festplatten. Einmal eingerichtet, lässt sich der Datenträger auf jedem Windows-PC ohne Installation entsperren und sperren – alle notwendigen Dateien liegen auf dem Datenträger selbst.

---

## Das Tool-Paar

| Programm | Zweck |
|---|---|
| **S-IT UsbSetup** | Einmalige Einrichtung: Partitionierung und AES-256-Verschlüsselung mit VeraCrypt |
| **S-IT UsbLock** | Täglicher Einsatz: Entsperren und Sperren auf Knopfdruck, bis zu drei Datenträger gleichzeitig |

---

## Funktionen

- 🛡️ AES-256-Verschlüsselung auf Basis von VeraCrypt
- 💻 Portabel – UsbLock startet direkt vom Datenträger, auf dem PC wird nichts installiert
- 🗂️ Bis zu drei S-IT-Datenträger gleichzeitig entsperrt
- ⚡ Schnelle Einrichtung – bei einer 500-GB-Festplatte etwa drei Minuten
- ⬇️ VeraCrypt wird beim ersten Einrichten in der neuesten Fassung von der offiziellen Quelle geladen
- 🔧 Neuen Datenträger direkt aus UsbLock einrichten

---

## Systemanforderungen

- Windows 10 / Windows 11 (64-Bit)
- Administratorrechte
- USB 3.0 oder USB-C empfohlen
- Externer Datenträger (mind. 2 GB)
- Einmalig Internetverbindung beim ersten Einrichten (VeraCrypt-Download, etwa 54 MB)

---

## Download

Aktuelle Version im [Release-Bereich](https://github.com/SattlerIT/sit-usblock/releases/latest) herunterladen, entpacken und `USB-Lock-Setup\S-IT-UsbSetup.exe` starten.

**Lieferumfang:**
- `S-IT-UsbLock.exe` mit Hilfe
- `USB-Lock-Setup\S-IT-UsbSetup.exe` mit Hilfe
- `Lizenz.txt`, `Disclaimer.txt`, `CHANGELOG.txt`

Projektseite: [sattlerit.github.io/sit-usblock](https://sattlerit.github.io/sit-usblock/)

---

## Hinweis zu Virenscannern

Da es sich um unabhängig entwickelte Software handelt, kann Windows SmartScreen oder eine Sicherheitssoftware die Programme beim ersten Start als unbekannt einstufen. Alle Dateien werden ausschließlich über diese GitHub-Seite veröffentlicht. Die SHA-256-Prüfsumme des aktuellen ZIP-Pakets steht auf der Projektseite.

---

## Lizenz

S-IT USB-Lock ist Freeware von Sattler IT-Service, Greifenstein. Nutzung und Weitergabe sind kostenlos erlaubt; kommerzielle Weiterverwendung oder Modifikation ohne Genehmigung ist nicht gestattet. Es gelten `Lizenz.txt` und `Disclaimer.txt`.

VeraCrypt ist ein eigenständiges Open-Source-Projekt und nicht Bestandteil von S-IT USB-Lock. Für VeraCrypt gelten dessen eigene Lizenzbedingungen (Apache License 2.0 und TrueCrypt License 3.0); die Lizenztexte legt das Setup im Ordner `VeraCrypt` ab.

---

## Kontakt & Spende

Kontakt: tool-entwicklung@sattler-it.de  
Spende: [PayPal](https://www.paypal.com/donate/?business=tool-entwicklung%40sattler-it.de&currency_code=EUR)  
Weitere Tools: [sattlerit.github.io/sattlerit-tools](https://sattlerit.github.io/sattlerit-tools/)

© 2026 Sattler IT-Service, Greifenstein · Autor: Hans Udo Sattler
