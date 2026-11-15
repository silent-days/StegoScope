# StegoScope v1

StegoScope is an offline steganography detection and digital-forensics GUI.
Choose your operating-system folder; do not run installers from another OS folder.

## Quick start

### Linux / Kali / Ubuntu

For a terminal installation:

```bash
cd Linux
bash install.sh
```

For the graphical installation wizard:

```bash
cd Linux
bash install-gui.sh
```

After installation, launch with `bash Linux/run.sh` or use the desktop menu entry.

### Windows 10/11

Open `Windows` and double-click `install-gui.bat`. For a terminal-style install,
run `install.bat` from that folder. Launch with `run.bat`.

### macOS

From Terminal:

```bash
cd macOS
bash install-macos.sh
```

Then launch with `bash macOS/run.sh` or double-click `macOS/StegoScope.command`.

## Folders

- `app/` — one canonical StegoScope source tree; do not delete it.
- `Linux/` — Linux terminal, GUI installer, launcher and uninstaller wrappers.
- `Windows/` — Windows batch installer, GUI installer, launcher and uninstaller wrappers.
- `macOS/` — macOS installer and launcher wrappers.
- `docs/` — installation, troubleshooting and project documentation.

Read `docs/INSTALL.md` if you need a detailed walkthrough. StegoScope requires
Python 3.11+ and keeps dependencies inside `app/.venv`; it does not modify the
system Python installation.
