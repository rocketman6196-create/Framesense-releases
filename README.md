# FrameSense

**Explains your game's performance.** Live FPS with 1% and 0.1% lows, a frame-time graph, CPU, GPU and RAM
health, what causes each stutter, which background apps cost you frames, and what to change. Free, for Windows 10
and 11.

**It never injects into games.** FrameSense reads only from Windows and your hardware sensors, so anti-cheat
systems have nothing to flag.

## Download

**[Download the latest version](https://github.com/rocketman6196-create/Framesense-releases/releases/latest/download/FrameSense-setup.exe)**
· [All versions and release notes](https://github.com/rocketman6196-create/Framesense-releases/releases)

Run `FrameSense-setup.exe`. It installs for your account only and needs no admin rights. Once installed, FrameSense
updates itself: when a new version has downloaded, it shows **Restart to update** (never while you're in a game).

### "Windows protected your PC"

The installer isn't code-signed yet, so SmartScreen may show this the first time. Click **More info**, then
**Run anyway**. Each release lists the installer's SHA-256 so you can check your download:

```powershell
Get-FileHash .\FrameSense-setup.exe
```

## Privacy

No account, no ads, no telemetry. FrameSense connects to the internet for only two things:

- a daily check here for a new version (Settings → About; you can turn it off), and
- a once-a-second ping to a game-server region you pick in the Network panel (off until you choose one).

## Report a problem

In FrameSense, open Settings → About → **Copy diagnostics**, then
[open a bug report](https://github.com/rocketman6196-create/Framesense-releases/issues/new/choose) and paste
them. Diagnostics list versions, hardware and permissions, and the last crash, but not your name or files.

## Support FrameSense

FrameSense is free. If it helped your games run better, you can support it from Settings → About →
**Support FrameSense** in the app.

---

This repository only holds installers and release notes. FrameSense's licence and the third-party licences it
ships with are in `THIRD-PARTY-LICENSES.txt` in the install folder.
