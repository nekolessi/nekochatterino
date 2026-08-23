# Neko's Chatterino

![Neko's Chatterino icon](./resources/icon.ico)

Neko's Chatterino is a personal, Windows-focused fork of
[Chatterino Homies](https://github.com/itzAlex/chatterino7), updated with the
changes from [Chatterino 2.5.5](https://github.com/Chatterino/chatterino2/releases/tag/2.5.5).

It keeps the extra Homies features while adding a polished portable build and
desktop-friendly system tray behavior.

## Download

Download the latest Windows portable build:

**[Neko's Chatterino 7.5.5 portable for Windows (64-bit)](https://github.com/nekolessi/NekoChatterino/releases/download/v7.5.5-neko.1/NekoChatterino-7.5.5-nightly-portable-windows-x64.zip)**

[View release notes and file checksum](https://github.com/nekolessi/NekoChatterino/releases/tag/v7.5.5-neko.1)

1. Download and extract the ZIP file.
2. Open the extracted `Chatterino2` folder.
3. Run `chatterino.exe`.

> [!NOTE]
> Neko's Chatterino is currently unsigned. Windows Smart App Control or an
> organization policy may block unsigned applications. Only download builds
> from this repository.

## Highlights

- Updated from Chatterino 2.5.2 to Chatterino 2.5.5.
- Includes the Chatterino Homies 7.5.2H1 feature set.
- Custom Neko's Chatterino branding and version information.
- Closing the main window minimizes it to the system tray.
- Click the tray icon to restore the window, or right-click it to exit.
- Correctly restores a maximized window.
- Portable-only release that keeps settings beside the application.
- Unsupported automatic update checks are disabled, avoiding false update
  alerts.
- Includes the Homies integrations and enhancements for services such as 7TV,
  BetterTTV, and FrankerFaceZ.

## Screenshots

![Example of global emotes](./resources/readme/global_emotes.png)
![Example of personal badges](./resources/readme/badges.png)

## Using the system tray

The **X** button hides Neko's Chatterino in the notification area instead of
ending it. Click the Neko's Chatterino tray icon to bring the app back. To close it
completely, right-click the tray icon and choose **Exit**.

## Issues and feedback

Report Neko's Chatterino problems in this repository's
[issue tracker](https://github.com/nekolessi/NekoChatterino/issues).

For an issue that also occurs in official Chatterino, use the
[upstream issue tracker](https://github.com/Chatterino/chatterino2/issues).

## Source and building

The current Neko's Chatterino work is on the
[`upgrade/chatterino-2.5.5` branch](https://github.com/nekolessi/NekoChatterino/tree/upgrade/chatterino-2.5.5).

```shell
git clone --recurse-submodules --branch upgrade/chatterino-2.5.5 https://github.com/nekolessi/NekoChatterino.git
```

See [Building on Windows](./BUILDING_ON_WINDOWS.md) for the upstream build
instructions.

## Credits and license

Neko's Chatterino is built on the work of:

- [Chatterino](https://github.com/Chatterino/chatterino2), a Twitch chat client.
- [Chatterino Homies](https://github.com/itzAlex/chatterino7), which provides the
  Homies feature set used by this fork.

This is an independent community fork and is not an official Chatterino or
Chatterino Homies release. The project remains available under the licenses in
this repository.
