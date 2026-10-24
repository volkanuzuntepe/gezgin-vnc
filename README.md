# Gezgin VNC

Universal remote desktop client and server for Windows — **free for personal and
commercial use** (freeware). This repository hosts the official installer;
Gezgin VNC is closed source.

**Download:** [GezginVNC_setup.exe](https://github.com/volkanuzuntepe/gezgin-vnc/releases/latest/download/GezginVNC_setup.exe)
from the [latest release](https://github.com/volkanuzuntepe/gezgin-vnc/releases/latest)
(verify with `SHA256SUMS.txt` there).

## Features

- **VNC (RFB 3.3–3.8)** — TightVNC, TigerVNC, UltraVNC, RealVNC, libvncserver;
  Tight, ZRLE, Hextile, H.264 encodings; VeNCrypt/TLS; file transfer; clipboard
- **RDP** — Windows 10/11 with NLA, clipboard, drive redirection
- **SPICE** — QEMU/KVM virtual machines
- **Share my desktop** — built-in server with one-time password, view-only mode
  and an ID-based relay for machines behind NAT
- Address book, Wake-on-LAN, SSH tunnelling

## Install

1. Download `GezginVNC_setup.exe` (link above).
2. Run it — no administrator rights needed (installs per user).
3. The installer is not code-signed yet, so Windows SmartScreen may warn:
   choose *More info → Run anyway*.

**H.264:** the codec is not bundled. Download Cisco's OpenH264 library from
*Settings → Video codec* inside the app ("OpenH264 Video Codec provided by
Cisco Systems, Inc.").

## License

Gezgin VNC is proprietary freeware, licensed under the
[End User License Agreement](EULA.en.md) (the [Turkish original](EULA.md)
prevails). You may use it free of charge and redistribute it unmodified.
Third-party notices are installed with the app and shown under *About*.

Please report problems in [Issues](../../issues).
