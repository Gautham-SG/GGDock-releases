# GG Dock

Installer and automatic updates for GG Dock, a Windows desktop helper with a drop-down panel, a Dynamic Island, voice commands, and League / TFT build cards. The source code is kept private; this repo only hosts the builds.

## Install

1. Download **[GGDock-win-Setup.exe](https://github.com/Gautham-SG/GGDock-releases/releases/latest/download/GGDock-win-Setup.exe)** and run it. It installs for your Windows user only, with no admin prompt.
2. Windows may say *"Windows protected your PC"*, because the app isn't code-signed. Click **More info**, then **Run anyway**. You only see this once.

## Updates

They're automatic. GG Dock checks for a new version shortly after it starts (never during a game) and downloads it in the background. When "Update ready" shows on the island, restart GG Dock (the ↻ button at the top right of the panel, or the tray menu). If you don't restart, the update installs the next time GG Dock starts.

## Voice commands

Voice uses Groq's free API with your own key. Get one at [console.groq.com](https://console.groq.com/keys) and paste it into GG Dock's Settings. Your key, settings and notes stay on your PC in `%APPDATA%\GGDock`; updates never touch them.

## Uninstall

Windows Settings → Apps → Installed apps → **GG Dock** → Uninstall.
