# Keka Bubble for Ubuntu

Download the installer from [Releases](https://github.com/Anujith9048/Keka-bubble-Ubuntu/releases/latest).

Requires **Ubuntu 24.04 desktop, 64-bit Intel/AMD (amd64)**.

Open a terminal in the downloaded file's folder and run:

```bash
sudo apt install ./keka-time-bubble_2.8.4_ubuntu24.04_amd64.deb
```

Launch **Keka Time Bubble** from the applications menu. Use your existing Chrome connector with the app.

The floating window uses X11/XWayland. Enable GNOME AppIndicator support for tray controls. Updates are installed manually with a newer Ubuntu package.

Build, package dependency resolution, unprivileged startup, window creation, and local bridge checks passed in Ubuntu 24.04 WSL. Live attendance and full desktop interaction still need verification on the target Ubuntu desktop.