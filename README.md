<p align="center">
  <img src="usbshortcutguard-logo.png" alt="USBShortcutGuard USB security logo" width="180">
</p>

<p align="center">
  <a href="https://github.com/johndimopoulos/USBShortcutGuard/releases/download/v3.0/USBShortcutGuard-Setup.exe">
    <img src="https://img.shields.io/badge/Download%20for%20Windows-0078D4?style=for-the-badge" alt="Download for Windows" height="40">
  </a>
  <br>
  <sub>Windows 10 / 11 · 64-bit · Version 3.0</sub>
</p>


# USBShortcutGuard — USB Shortcut Virus Removal for Windows

[Ελληνικά — Οδηγός στα Ελληνικά](README.el.md)

USBShortcutGuard 3.0 helps clean USB flash drives affected by shortcut viruses on **Windows 10 and Windows 11 (64-bit)**. It quarantines files matching strong shortcut-virus signatures and restores the visibility of affected original files and folders.

If your USB folders appear as shortcuts or your files have become hidden, USBShortcutGuard checks for the patterns associated with this type of infection.

## Download USBShortcutGuard

[Download USBShortcutGuard 3.0 for Windows](https://github.com/johndimopoulos/USBShortcutGuard/releases/download/v3.0/USBShortcutGuard-Setup.exe) · [Release notes and SHA-256 checksum](https://github.com/johndimopoulos/USBShortcutGuard/releases/tag/v3.0)

1. Download **USBShortcutGuard-Setup.exe** and **SHA256SUMS.txt** from the release.
2. Compare the installer's SHA-256 hash with the checksum provided.
3. Run the installer and approve the Windows administrator prompt.
4. Allow the USB check to finish before opening suspicious shortcuts.

## Features

- Checks USB storage connected at startup and inserted later.
- Examines suspicious shortcuts, autorun commands and related scripts without executing them.
- Quarantines confirmed shortcut-virus files and restores hidden/system attributes on affected originals.
- Shows scan results through Windows notifications and progress for checks lasting longer than five seconds.
- Provides an administrator-only quarantine viewer with copying and permanent deletion.
- Supports **English and Greek**: Greek Windows display language selects Greek; other display languages select English.

## Installation and existing installations

Windows 10 or Windows 11, a 64-bit system and administrator approval are required. Instructions can be reopened from the application's Start menu folder.

**Reinstall/update** preserves application logs and quarantined files. **Complete reinstall** and **uninstall** delete them.

## Frequently asked questions

### Can it restore hidden USB files and folders?

It restores visibility for existing originals associated with a confirmed shortcut-virus infection. It does not recover deleted file contents.

### Is this a complete antivirus?

No. USBShortcutGuard targets USB shortcut-virus patterns. It does not replace antivirus software or remove an infection from Windows itself. Use Windows Defender or another antivirus to inspect an infected computer.

### Will every script be quarantined?

No. A file extension alone is not enough to trigger quarantine. Ordinary scripts should remain unchanged; detection depends on suspicious content and context.

## Support and feedback

[Report a bug](https://github.com/johndimopoulos/USBShortcutGuard/issues/new/choose) or [ask a question and suggest improvements](https://github.com/johndimopoulos/USBShortcutGuard/discussions).

For display problems, include the Windows version, screen resolution, scaling percentage and a screenshot with personal information removed. Do not upload suspected malware, quarantined files, passwords or personal data.

## Project and source code

This is the official public repository for USBShortcutGuard documentation, installer releases and feedback. Application source is maintained separately in a private repository.

John Dimopoulos — Software Engineer / IT Professor.
