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

```powershell
choco install advanced-renamer, audacity, audacity-ffmpeg, audacity-lame, calibre, ccleaner, cheatengine, discord, Everything, f.lux, ffmpeg, git, github-desktop, greenshot, handbrake, marktext, microsoft-windows-terminal, musicbee, neovim, nodejs, notion, obs-studio, pandoc, peazip, potplayer, powertoys, protonvpn, python3, qbittorrent, scrcpy, spotify, telegram, vscode, wox, xdm, youtube-dl -y
```

## List of other useful programs

* Edge Dev Branch, Microsoft To-Do, Microsoft Your Phone, Proton VPN, WO Mic

* [oh-my-posh](https://github.com/JanDeDobbeleer/oh-my-posh)

## Additional Steps (for some programs)

* Wox: manually enable `Everything` module.
* Greenshot: `Ctrl + Alt + Shift + i`
* scrcpy: Enable DPI override `scrcpy.exe -> Properties -> Compatibility -> Change high DPI setting -> Check -> Application`

## Removed Programs

```diff
- nomacs: default photos app is better
- mailspring: default mail app is better
- cmder: win-terminal is better
```
