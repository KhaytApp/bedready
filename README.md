# Bed Ready — downloads

**Bed Ready** is a free desktop workbench for solo 3D-printing makers: organise your print
files, preview them in 3D, retarget any model to the printer you own, plan colours, and cost
every print. It works alongside your existing slicer — it doesn’t replace it.

> **Public beta.** Expect rough edges, keep backups, and send feedback at **https://bedready.io**.
> This repo hosts the **downloads only**; the source lives in
> [KhaytApp/Khayt](https://github.com/KhaytApp/Khayt) (source-available, FSL-1.1-Apache-2.0).

## Download (latest beta: v1.0.0-beta.1)

| Platform | File |
|---|---|
| **macOS** (Apple Silicon) | [BedReady-1.0.0-beta.1-mac-arm64.dmg](https://github.com/KhaytApp/bedready/releases/download/bedready-v1.0.0-beta.1/BedReady-1.0.0-beta.1-mac-arm64.dmg) |
| **Windows** (installer) | [BedReady-1.0.0-beta.1-win-x64-Setup.exe](https://github.com/KhaytApp/bedready/releases/download/bedready-v1.0.0-beta.1/BedReady-1.0.0-beta.1-win-x64-Setup.exe) |
| **Windows** (portable) | [BedReady-1.0.0-beta.1-win-x64-portable.exe](https://github.com/KhaytApp/bedready/releases/download/bedready-v1.0.0-beta.1/BedReady-1.0.0-beta.1-win-x64-portable.exe) |
| **Linux** (AppImage) | [BedReady-1.0.0-beta.1-linux-x64.AppImage](https://github.com/KhaytApp/bedready/releases/download/bedready-v1.0.0-beta.1/BedReady-1.0.0-beta.1-linux-x64.AppImage) |
| **Linux** (.deb) | see the [latest release](https://github.com/KhaytApp/bedready/releases/latest) |

All installers are also on the **[Releases page](https://github.com/KhaytApp/bedready/releases/latest)**.

## Installing

**macOS** — this beta is **not notarized**, so Gatekeeper will complain the first time.
Open the `.dmg`, drag **Bed Ready** to Applications, then either:

- **Right-click** the app → **Open** → **Open** (only needed once), or
- if it says *“damaged / can’t be opened”*, clear the download quarantine:
  ```bash
  xattr -dr com.apple.quarantine "/Applications/Bed Ready.app"
  ```

**Windows** — run the **Setup** installer, or use the **portable** `.exe` (no install).
SmartScreen may warn on an unsigned beta → **More info** → **Run anyway**.

**Linux** — `chmod +x BedReady-*.AppImage` then run it, or install the `.deb`
(`sudo apt install ./BedReady-*.deb`).

## For the website (bedready.io)

Link the buttons to the URLs in the table above. When a new beta ships, the version in
each filename changes — either update the links, or link to
`https://github.com/KhaytApp/bedready/releases/latest` and let visitors pick the newest.

---

Not affiliated with, sponsored by, or endorsed by Snapmaker, Bambu Lab, Prusa, Creality,
UltiMaker or any other maker; product names are used only to describe compatibility.
