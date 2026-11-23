# Rumbler keyboard

Android voice typing and keyboard customization, maintained by **Chinmay Shastry (Paradox)**.

Rumbler keyboard is a renamed fork of [PixelBoard](https://github.com/Akshayykadam/PixelBoard), an open-source patch project for Gboard. It is an independent project, not an official Google Pixel keyboard and not affiliated with Google.

<img src="rumbler-icon.png" width="160" alt="Rumbler keyboard icon" />

## Build status

Branding preparation is in progress. **No Rumbler keyboard APK has been built or tested yet.** Do not mistake upstream PixelBoard downloads for a Rumbler release.

- The requested display name is configured in `options.json`.
- The supplied icon is stored in `rumbler-icon.png`; application-resource integration is still pending.
- Package isolation, in-app branding, update URLs and attribution screens still require review before a release.

## Voice typing and live dictation

Upstream PixelBoard includes patches for Rambler natural voice dictation and AI writing tools. These features are inherited patch targets, not a claim that this fork has passed device testing. Availability depends on the compatible Gboard base, Android version, supported language, device and Google services. A keyboard dictation feature is not a general-purpose recorder for calls or other apps' audio.

## Building

This repository contains patch source, not the complete source of Google's keyboard. A compatible, lawfully obtained Gboard base APK is required; it is not included here. Review the upstream build documentation and current patch compatibility before building. No GitHub Actions build has been started for this fork.

## Credits and license

Fork maintainer and Rumbler branding: Chinmay Shastry. Original PixelBoard work: Akshay Kadam and the upstream contributors, including the foundational Gboard patch research credited by that project. Existing source copyright notices are retained. Changes made for this fork must be marked and the GPL-covered corresponding source made available with distributed patch binaries.

The patch project is licensed under [GNU GPL v3](LICENSE). That license does not grant rights to Google's proprietary Gboard code, models, services, trademarks or other third-party assets. Google, Gboard, Pixel, Android and Gemini are trademarks of their respective owners. This fork must not be marketed as an official Google product.

See [upstream documentation](https://github.com/Akshayykadam/PixelBoard) for historical feature descriptions and contributors.
