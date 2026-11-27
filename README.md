# Sets

**Five Mac apps that organize your work into projects: folders, terminals, text files, web pages, and a menu bar app that opens them together.**

This repository distributes the apps and is the place to report problems. Downloads are on the
[Releases](https://github.com/RayKitajima/Sets/releases/latest) page.

| App | Handles | Guide |
| --- | --- | --- |
| FolderSet | Folders (a file manager) | [craftclay.com/folderset](https://www.craftclay.com/folderset/) |
| TerminalSet | Terminals | [craftclay.com/terminalset](https://www.craftclay.com/terminalset/) |
| EditorSet | Text files (a plain-text editor) | [craftclay.com/editorset](https://www.craftclay.com/editorset/) |
| BrowserSet | Web pages (a web browser) | [craftclay.com/browserset](https://www.craftclay.com/browserset/) |
| SetCenter | A menu bar app that controls the four apps above together | [craftclay.com/setcenter](https://www.craftclay.com/setcenter/) |

Each app can be used on its own. A project is a named set of things the app opens together; projects with the
same name in the four apps form one workspace in SetCenter.

## Requirements

- macOS 26.0 or later
- A Mac with Apple silicon

## Installation

1. Download `Sets-<version>.dmg` from the [latest release](https://github.com/RayKitajima/Sets/releases/latest).
2. Open the disk image and drag the `Sets` folder onto the `Applications` shortcut next to it.
3. Launch the apps you want from `Applications/Sets`.

You can keep only the apps you use; delete the others from the folder. SetCenter needs at least one of the other four.

The apps are signed with a Developer ID and notarized by Apple. There is no automatic update: to update,
download the new disk image and replace the folder.

To check a download, compare it with the `.sha256` file attached to the same release:

```bash
shasum -a 256 -c Sets-<version>.dmg.sha256
```

## Privacy

No accounts, cloud sync, ads, or telemetry. The apps do not check for updates. BrowserSet loads the pages you open;
the other apps do not communicate with external servers.

## Reporting a problem

Open an [issue](https://github.com/RayKitajima/Sets/issues) and say which app and version it is about
(the version is in the app's About window), your macOS version, and the steps that lead to the problem.
Do not attach screenshots or logs that show private information.

Copyright © 2026 Ray Kitajima.
