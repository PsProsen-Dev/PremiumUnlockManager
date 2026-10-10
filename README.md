# Premium Unlocker Manager

Unlock premium features in popular Android apps — a ReVanced-style patcher with a premium red monogram brand.

## Version

**v1.25.7** — debug build

## Features

- **88 apps** supported, **288 patches** bundled
- **4 patch sources**: ReVanced Official (default), anddea (RVX), Morphe patches, Piko/crimera
- **MicroG RE v7.2.1** support — dedicated dashboard card with install detection and direct APK download for Google login on patched YouTube / YouTube Music
- **Asset-first patch loading** — patches load instantly from bundled assets, no GitHub API dependency (DMCA 451-proof)
- RVX Manager-style app list: icon, app name, version, patch count, suggested version
- Patch sources selectable in Settings → Alternative sources

## Supported apps (highlights)

YouTube (60 patches), YouTube Music (19), Instagram, TikTok / TikTok Asia (10), Strava (8), X/Twitter (7), Twitch, Spotify (5), Messenger (4), Reddit + clients (30+), SoundCloud (3), Google Photos, Duolingo, Adobe Lightroom, Prime Video, Facebook (2) — plus 72 more.

## Downloads

Grab the latest APK from the [Releases](https://github.com/PsProsen-Dev/premium-unlocker-manager/releases) page:
`premium-unlocker-manager-v1.25.7.apk`

## Requirements

- Android 8.0+
- MicroG RE v7.2.1 (for patched Google apps login) — download from the in-app dashboard card or https://github.com/MorpheApp/MicroG-RE/releases

## Branding

- App label: **Premium Unlock Manager**
- Package: `app.unlockmanager.manager.flutter`

## Notes

- This is a private development repo. Builds are debug APKs produced from the `revanced-manager` fork with full rebranding (17+ files changed: launcher name, applicationId, namespace, Kotlin package, MethodChannels, APK signer, User-Agent).
- Exported patched APKs are named `*-unlocked_v*.apk`.

---

Built with Flutter. Maintained by [PsProsen-Dev](https://github.com/PsProsen-Dev).
