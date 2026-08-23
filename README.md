# blnk - Base Mobile

Native Kotlin/Jetpack-Compose administration app for blnk - Base. The app uses
the authenticated app API directly and contains no WebView or PWA wrapper.

## Current preview

Version `0.9.7-preview` (version code 20) provides the native mobile feature set
for infrastructure, instances, voice servers, MSG servers, websites, backups,
users, roles, system administration, and settings.

The APK is published in the
[`v0.9.7-preview` release](https://github.com/blnk-projects/BlenkBase-Mobile/releases/tag/v0.9.7-preview).

Preview builds up to and including 0.9.5 used a retired local test signature.
Android therefore requires those builds to be uninstalled once before 0.9.7
can be installed. Starting with 0.9.7, normal in-app updates use the permanent
product signing identity and `mobile-update-manifest-v2.json`. The old manifest
remains pinned to 0.9.5 so it cannot offer an incompatible update.
