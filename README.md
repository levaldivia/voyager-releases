# Voyager for macOS

Voyager is a native development environment for Apple Silicon Macs running macOS 15 or later.

Installers appear on GitHub Releases once a signed build has been published.

## Download and install

- [Stable — latest release](https://github.com/levaldivia/voyager-releases/releases/latest): the default for everyday use.
- [All releases, including Nightly](https://github.com/levaldivia/voyager-releases/releases): Nightly builds are marked as prereleases.

Once a release is available, download its **DMG**, open it, drag **Voyager.app** onto **Applications**, then eject the disk image and launch Voyager from Applications. ZIP assets are used for automatic updates.

## Choose your updates

Open **Voyager → Update Settings…** and select **Stable** or **Nightly**.

Stable receives releases selected for general use. Nightly receives tested builds after changes merge. Your choice persists across app updates; both channels use the same workspaces and conversations.

Switching back to Stable keeps your current version until a newer Stable release is available. Finish a pending update before changing channels if settings asks you to.

## Distribution

This repository hosts installers and signed update feeds only. Voyager's source repository is private. Release assets will be Developer ID signed and notarized; Sparkle verifies update signatures before installation.
