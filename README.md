# 🚨 zReport - Advanced Player Report System

Ein hochmodernes Report-System für Minecraft-Server mit GUI-Menüs und Admin-Tools.

## ✨ Features

- 📝 **Einfache Reports** mit `/report <Spieler> <Grund>`
- 👮 **Admin-Interface** mit `/reportinfo`
- 📂 **Automatische Speicherung** aller Reports
- 🔔 **Echtzeit-Benachrichtigungen** für Admins
- 🖥️ **Intuitive Menüs** mit Bestätigungsdialogen
- 📊 **Report-Statistiken** pro Spieler
- 🔒 **Berechtigungssystem** (`r.use` und `r.admin`)

## 📦 Installation

1. Platziere die `.jar`-Datei im `plugins`-Ordner
2. Starte deinen Server neu
3. Konfiguriere die Berechtigungen nach Bedarf

## 🎮 Commands

| Command | Beschreibung | Berechtigung |
|---------|-------------|--------------|
| `/report <Spieler> <Grund>` | Melde einen Spieler | `r.use` (default: true) |
| `/reportinfo` | Zeige alle Reports an | `r.admin` (default: op) |

## 🔧 Permissions

```perms
permissions:
  r.use:
    description: Erlaubt das Nutzen des Report-Systems
    default: true
  r.admin:
    description: Erlaubt das Anzeigen und Bearbeiten von Reports
    default: op
