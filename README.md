# Chocolatey Packages

Backup of some useful programs available via chocolatey

## Installing choco

Enter the following commands in powershell with **admin privilege**

```powershell
Set-ExecutionPolicy AllSigned
```

```powershell
Set-ExecutionPolicy Bypass -Scope Process -Force; [System.Net.ServicePointManager]::SecurityProtocol = [System.Net.ServicePointManager]::SecurityProtocol -bor 3072; iex ((New-Object System.Net.WebClient).DownloadString('https://chocolatey.org/install.ps1'))
```

## Installing packages

```bash
choco install advanced-renamer, audacity, audacity-ffmpeg, audacity-lame, calibre, ccleaner, cheatengine, Cmder, discord, Everything, f.lux, ffmpeg, filebot, git, github-desktop, greenshot, handbrake, marktext, musicbee, neovim, nodejs, nomacs, notion, obs-studio, pandoc, peazip, potplayer, powertoys, protonvpn, python3, qbittorrent, scrcpy, spotify, telegram, wox, xdm, youtube-dl -y
```

## List of other useful programs

* Edge Dev Production
  
  * Choco has problems updating this package. Chromium self-updates just fine.

* Mailspring

* Microsoft To-Do

* Microsoft Your Phone

* Proton VPN

* WO Mic

## Additional Steps (for some programs)

### Cmder

[Add Cmder to context menu](https://gist.github.com/hamzahamidi/ce00cdc5895480b9d538093bdeda4334), enable quake-style, and set to **start as admin** in properties of `cmder.exe`

### Wox

Manually enable `Everything` module.

### Greenshot

`Ctrl + Alt + Shift + i`

### scrcpy

Enable DPI override

`scrcpy.exe -> Properties -> Compatibility -> Change high DPI setting -> Check -> Application`
