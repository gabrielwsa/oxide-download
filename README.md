<p align="center">
  <img src="icon.png" width="96" alt="Oxide">
</p>

<h1 align="center">Oxide</h1>

<p align="center">
  A desktop API client: send requests, organize collections, write tests,<br>
  run mock servers and share your workspace with your team.
</p>

<p align="center">
  <a href="../../releases/latest"><b>⬇ Download the latest version</b></a>
</p>

---

## Download

Pick the file for your computer on the [latest release](../../releases/latest):

| System | File |
|---|---|
| **Windows** | `Oxide-Setup-x.y.z.exe` |
| **macOS** — Apple Silicon (M1, M2…) | `Oxide-x.y.z-arm64.dmg` |
| **macOS** — Intel | `Oxide-x.y.z-x64.dmg` |
| **Linux** — any distribution | `Oxide-x.y.z.AppImage` |
| **Linux** — Arch | `Oxide-x.y.z-x86_64.pkg.tar.xz` |

Not sure which Mac you have? Open the Apple menu → **About This Mac**: it says "Apple chip" or "Intel".

## Install

- **Windows** — run the installer. If Windows says it protected your PC, click **More info → Run anyway**.
- **macOS** — open the `.dmg` and drag Oxide to **Applications**. The first time, right-click the app and choose **Open**.
- **Linux (AppImage)** — make the file executable (right-click → Properties → "Allow executing", or `chmod +x`) and open it. It adds itself to your applications menu.
- **Arch Linux** — install it with `sudo pacman -U Oxide-*.pkg.tar.xz`.

The installers are not digitally signed yet, which is why Windows and macOS ask for confirmation the first time.

## Updates

Oxide checks for new versions when it opens and every few hours, and shows a notice at the top of the window.
On Windows, Linux and Arch it downloads and installs the update for you; on macOS it opens this page.
After each update, a **What's new** window shows what changed.

## Your data

Your collections, environments and history stay on your computer.
If you turn on Git versioning, they are also saved to the repository you choose (GitHub, GitLab…), and nowhere else.

<sub>Formerly known as RequestPost. The "Source code" files GitHub attaches to each release only contain this page.</sub>
