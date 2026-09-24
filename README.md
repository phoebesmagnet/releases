# Phoebe's Magnet

<p><em>A tiny media player that only plays <code>magnet:</code> links.</em></p>

Paste a magnet link, or click one in your browser, and it starts playing while it downloads.

Feedback and suggestions welcome from [the discussions page](https://github.com/orgs/phoebesmagnet/discussions).

## Download

Get the latest version from the **[Releases page](https://github.com/phoebesmagnet/releases/releases/latest)**.

| Platform | File |
|---|---|
| macOS (Apple Silicon & Intel) | `.dmg` |
| Windows | `-setup.exe` (or `.msi`) |
| Linux | `.AppImage`, `.deb` (Debian/Ubuntu) or `.rpm` (Fedora) |

## Installing

**macOS:** Open the `.dmg` and drag Phoebe's Magnet into Applications.

**Windows:** Run the installer. If Windows shows "Windows protected your PC", click **More info → Run anyway**.

**Linux:** Install the `.deb` or `.rpm` with your package manager, or make the AppImage executable and run it:

    chmod +x Phoebes.Magnet_*.AppImage
    ./Phoebes.Magnet_*.AppImage

## Opening magnet links

To have magnet links from your browser open in Phoebe's Magnet, use the option on the app's start screen to make it your default app for `magnet:` links.

The AppImage command uses Phoebes.Magnet_* as a guess. GitHub replaces the space and apostrophe in uploaded file names, and I haven't seen the actual name yet. After your first release, check the file name on the Releases page and fix that line if it's different.
