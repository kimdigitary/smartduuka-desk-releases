# SmartDuuka Desk downloads

SmartDuuka Desk turns a Windows computer with a USB fingerprint reader into a check-in desk for a
SmartDuuka business networking chapter. Members touch the reader and are checked in to the meeting.

## Download

**[Download SmartDuuka Desk for Windows](https://github.com/kimdigitary/smartduuka-desk-releases/releases/latest/download/SmartDuukaDeskSetup.exe)**

This link always gives the newest version. Every version is listed under
[Releases](https://github.com/kimdigitary/smartduuka-desk-releases/releases).

- Windows 10 or 11, 64-bit.
- A supported USB fingerprint reader (ZKTeco, SecuGen, DigitalPersona / HID) with its maker's driver
  installed, or a laptop's built-in sensor.
- An internet connection. Check-ins made while the internet is down are saved and sent later.

## Install

1. Plug in the fingerprint reader and install its driver from the maker.
2. Run `SmartDuukaDeskSetup.exe`. It installs for the Windows user who runs it; no administrator is needed.
   If Windows shows "Windows protected your PC", choose **More info**, then **Run anyway**.
3. In SmartDuuka, open **Chapter > Check-in Desks**, add a desk and copy its setup code.
4. Paste the code into SmartDuuka Desk, then approve the desk on the Check-in Desks page with the
   6-digit number the desk shows.

## Updates

SmartDuuka Desk 1.0.2 and later update themselves. When a new version is out the desk shows
"SmartDuuka Desk is ready" with an **Update now** button; the menu also has **Check for updates**.
Updates are signed: a desk installs a download only when it matches the signed `latest.json`.

## Check a download

Each release has `SHA256SUMS.txt`. In PowerShell:

```powershell
Get-FileHash .\SmartDuukaDeskSetup.exe -Algorithm SHA256
```

The hash must match the line for the file in `SHA256SUMS.txt`.

## Help

Visit [smartduuka.com](https://smartduuka.com) or contact SmartDuuka support.

© Digivolve Technologies Limited
