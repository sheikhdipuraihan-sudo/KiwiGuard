# KiwiGuard for Kiwi Browser

KiwiGuard is a Kiwi Browser-focused, mobile-first content blocker based on the uBlock Origin codebase and released under the GNU General Public License v3. It blocks advertising, tracking, malware, abusive resources, cookie prompts, and other page annoyances while keeping the mature dynamic filtering, logger, element picker, and backup/restore workflows.

## What changed in this fork

- Rebranded user-facing UI as **KiwiGuard** while retaining upstream attribution and licensing.
- Corrected the automatic update feed to this repository.
- Updated the extension version to `1.38.0.0`.
- Strengthened fresh-install defaults with mobile ads, tracking protection, URL tracking protection, and cookie-annoyance coverage.
- Added a polished, compact Kiwi Browser popup header and touch-friendly visual treatment.

## Install on Kiwi Browser

1. Download the latest release package from the [Releases](https://github.com/sheikhdipuraihan-sudo/uBlock-Kiwi/releases) page.
2. In Kiwi Browser, open the extensions page and enable Developer mode.
3. Load the unpacked `stable` directory, or install the packaged extension supplied in the release.
4. Open KiwiGuard and refresh filter lists after installation.

KiwiGuard is designed for Kiwi Browser on Android. It is not a replacement for the full upstream uBlock Origin project on desktop browsers. Filter lists are maintained by their respective upstream authors; KiwiGuard only selects and bundles compatible sources.

## License and attribution

KiwiGuard remains a GPLv3 derivative of uBlock Origin. See `stable/LICENSE.txt` for the complete license and attribution notices.
