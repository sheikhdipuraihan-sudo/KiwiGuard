# KiwiGuard for Kiwi Browser

KiwiGuard is a Kiwi Browser-focused, mobile-first content blocker based on the current uBlock Origin Chromium Manifest V2 engine and released under the GNU General Public License v3. It blocks advertising, tracking, malware, abusive resources, cookie prompts, and other page annoyances while keeping uBlock Origin's mature dynamic filtering, logger, element picker, scriptlets, and backup/restore workflows.

## KiwiGuard engine rebase

This release rebases the extension package on the current upstream uBlock Origin Chromium MV2 build. Kiwi-specific changes are layered on top: the KiwiGuard name and popup treatment, Kiwi update metadata, and a curated mobile/privacy first-run filter profile.

KiwiGuard is designed for Kiwi Browser on Android. It is not a replacement for the upstream project on desktop browsers. Filter lists and the blocking engine retain upstream attribution and licensing.

## Install

1. Download the latest release package from the [Releases](https://github.com/sheikhdipuraihan-sudo/uBlock-Kiwi/releases) page.
2. In Kiwi Browser, open the extensions page and enable Developer mode.
3. Load the unpacked `stable` directory, or install the packaged extension supplied in the release.
4. Open KiwiGuard and refresh filter lists after installation.

## License and attribution

KiwiGuard remains a GPLv3 derivative of uBlock Origin. See `stable/LICENSE.txt` for the complete license and attribution notices.
