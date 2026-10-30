# OpenEnsemble Desktop

The desktop client for your OpenEnsemble server, available for **Windows x64**
and **Linux x64**.

**[Download for your computer](https://openensemble.github.io/openensemble/desktop/)** ·
**[Latest release](https://github.com/openensemble/desktop/releases/latest)**

The OE webpage selects the download for your operating system and also offers
both platform choices. This repository hosts installers and update metadata;
the OpenEnsemble server lives in [openensemble/openensemble](https://github.com/openensemble/openensemble).

## Install

- **Windows:** download `OpenEnsemble-Setup-<version>-x64.exe`, open it, and follow
  the installer. Launch OpenEnsemble from the Start menu or desktop shortcut.
- **Linux:** download `OpenEnsemble-<version>-x86_64.AppImage` into a folder you
  own, such as `~/Applications`. In Properties, allow the file to run as a
  program, then open it. Keep this folder writable for updates.

Choose your OE server from the network search, or enter its HTTPS address,
then sign in with your existing account. The client does not install a server.

The Windows installer is currently unsigned. Windows may show an
unknown-publisher or SmartScreen notice. The release includes SHA-256 checksums.

## Updates

The app checks for new stable releases shortly after startup and every six
hours. When prompted, save your work and choose **Update and restart**. It
downloads and verifies the release, updates in place, and reopens. Settings,
sign-in storage and local files remain in their existing locations.

Checking does not download or install updates. Closing the app without
accepting the update does not install anything. You can check immediately under
**App updates → Check for updates**.

Windows clients from version 0.2.0 already use this feed. Version 0.1.0 requires
a one-time manual installation. Linux users running from source need to switch
to the AppImage to enable updates.

[Desktop guide](https://openensemble.github.io/openensemble/guide/desktop-app/) ·
[OpenEnsemble website](https://openensemble.github.io/openensemble/)
