# RustDesk for 4h1m — downloads

Pre-configured [RustDesk](https://rustdesk.com) clients for the 4h1m remote-support server.
Built automatically from each upstream RustDesk release; nothing to configure after install.

**[⬇ Latest release](https://github.com/4H1Mzs/rustdesk4him-releases/releases/latest)**

| Platform | File |
|----------|------|
| Windows 10/11 (64-bit) | `rustdesk-<version>-x86_64.exe` (portable installer) or `rustdesk-<version>-x86_64.msi` |
| macOS (Apple Silicon) | `rustdesk-<version>-aarch64.dmg` — signed and notarized |
| Linux (x86_64, glibc ≥ 2.35) | `rustdesk-<version>-x86_64.deb` or `rustdesk-<version>-x86_64.AppImage` |
| Android (arm64) | `rustdesk-<version>-aarch64.apk` |

Windows builds are not code-signed; SmartScreen will ask once ("More info → Run anyway").

## Updates

The app checks for new versions on start and shows an **Update** button when this repository
has a newer release. On Windows it can download and install the update itself
(Settings → General → *Allow auto update*); on other platforms the button opens the release
page.

## Source

Built from unmodified [rustdesk/rustdesk](https://github.com/rustdesk/rustdesk) at the tagged
version, with the 4h1m server address, key and logo baked in. Build automation lives in a
private repository.
