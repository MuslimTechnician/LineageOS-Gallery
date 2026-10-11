# Gallery (LineageOS Glimpse)

Sideloadable build of [LineageOS Glimpse](https://github.com/LineageOS/android_packages_apps_Glimpse) — the Material You gallery app — as a normal installable APK for any Android 11+ ROM.

- **Package:** `org.lineageos.gallery` (installs alongside the system gallery)
- **Tracked branch:** `lineage-24.0` (current official LineageOS)
- **Auto-synced:** a daily job builds a new release whenever official commits land

## Install

Grab the latest `.apk` from [Releases](../../releases) and install it (sideload / file manager).

## Versioning

`versionName` = `24.0-<YYYY.MM.DD>`, `versionCode` = `<YYYYMMDD>`. One release per upstream change.

## Notes

Sideloaded apps can't hold Android's `MANAGE_MEDIA` / system-gallery role, so delete/trash shows a confirmation prompt. Everything else works normally.
