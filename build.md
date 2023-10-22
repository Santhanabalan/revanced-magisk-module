YouTube: 18.41.35  
Music-Extended (arm64-v8a): 6.23.54  
Music-Extended (arm-v7a): 6.23.54  
YouTube-Extended: 18.41.35  
Music (arm64-v8a): 6.23.54  
Music (arm-v7a): 6.23.54  
Instagram: 305.0.0.34.110  

Install [Vanced Microg](https://github.com/TeamVanced/VancedMicroG/releases) for non-root YouTube or YT Music  

[revanced-magisk-module](https://github.com/Santhanabalan/revanced-magisk-module)  

---
Changelog:  
CLI: inotia00/revanced-cli-4.0.3-all.jar  
Integrations: inotia00/revanced-integrations-0.120.1.apk  
Patches: inotia00/revanced-patches-2.195.1.jar  

YouTube
==
- feat(YouTube): add support version `v18.40.34`
- feat(YouTube): add `Custom player overlay opacity` patch
- feat(YouTube): add `Spoof device dimensions` patch https://github.com/inotia00/ReVanced_Extended/issues/1582
- feat(YouTube): change patch name `Bypass ambient mode restrictions` → `Ambient mode switch`
- feat(YouTube): remove `Enable new comment popup panels` patch (It can now be used without a patch even on YouTube v18.24.37, the minimum supported version)
- feat(YouTube): remove `Hide player overlay filter` patch
- feat(YouTube/Ambient mode switch): add `Disable ambient mode`, `Disable ambient mode in fullscreen` settings
- feat(YouTube/Custom speed overlay): remove `Disable speed overlay` settings (fix https://github.com/inotia00/ReVanced_Extended/issues/1574)
- feat(YouTube/Hide general ads): update adblock filter
- feat(YouTube/Hide layout components): add `Hide start trial button` settings
- feat(YouTube/Hide navigation buttons): `Open library on app startup` now also works in the `You` tab (`Open library on app startup` → `Open library(You) on app startup`)
- feat(YouTube/Hide quick actions): add `Hide open mix playlist button`, `Hide open playlist button` settings https://github.com/inotia00/ReVanced_Extended/issues/1591
- feat(YouTube/Spoof app version): add target version 18.33.40 - Restore old shorts action bar
- fix(YouTube/Custom speed overlay): change setting description https://github.com/inotia00/ReVanced_Extended/issues/1575
- fix(YouTube/Default playback speed): change default value
- fix(YouTube/Default video quality): video quality toast shows wrong quality value https://github.com/inotia00/ReVanced_Extended/issues/1589
- fix(YouTube/Disable haptic feedback): separate the `Disable seek undo haptic feedback` setting from the `Disable seek haptic feedback` setting https://github.com/inotia00/ReVanced_Extended/issues/1566
- fix(YouTube/Enable old quality layout): sometimes patch not working on tablets https://github.com/inotia00/ReVanced_Extended/issues/1507
- fix(YouTube/Enable wide search bar): wide search bar does not apply to You tab https://github.com/inotia00/ReVanced_Extended/issues/1572
- fix(YouTube/Force video codec): no longer spoofing device dimensions https://github.com/inotia00/ReVanced_Extended/issues/1582
- fix(YouTube/Hide button container): change settings name `Hide playlist button` → `Hide save to playlist button`
- fix(YouTube/Hide latest videos button): `Hide latest videos button` setting is not disabled on tablets https://github.com/inotia00/ReVanced_Extended/issues/1596
- fix(YouTube/Hide layout components): `Hide official header` doesn't work (A/B tests) https://github.com/inotia00/ReVanced_Extended/issues/1573
- fix(YouTube/Hide navigation buttons): change description of `Switch create button with notifications button` setting https://github.com/inotia00/ReVanced_Extended/issues/1563
- fix(YouTube/Hide player button background): fade out animation of the player button background is unnatural
- fix(YouTube/Hide player flyout panel): change default value
- fix(YouTube/Hide player flyout panel): If any component belonging to `Additional settings` is hidden, the entire `Additional settings` menu is hidden https://github.com/inotia00/ReVanced_Extended/issues/1569
- fix(YouTube/Hide player flyout panel): video quality menu is hidden in the old player flyout panel when enabling the Spoof app version
- fix(YouTube/Hide quick actions): change settings name `Hide playlist button` → `Hide save to playlist button`
- fix(YouTube/Hide seek message): separate the `Hide seek undo message` setting from the `Hide seek message` setting https://github.com/inotia00/ReVanced_Extended/issues/1566
- fix(YouTube/Hide shorts components): menu button is not hidden on tablets https://github.com/inotia00/ReVanced_Extended/issues/1567
- fix(YouTube/Hide shorts components): settings not available on tablets are not disabled on tablets
- fix(YouTube/Hide shorts components): toolbar buttons in shorts are not hidden unless you include the `Hide toolbar button` patch
- fix(YouTube/Hide shorts components): `Hide shorts shelf` hides `Official Header` (A/B tests)
- fix(YouTube/Hide suggestions shelf): change setting description https://github.com/inotia00/ReVanced_Extended/issues/1586
- fix(YouTube/Hide suggestions shelf): playlist shelf is hidden in You tab on tablet
- fix(YouTube/Hide toolbar button): create button is not hidden on tablets https://github.com/inotia00/ReVanced_Extended/issues/1568
- fix(YouTube/Litho filter): no longer using `Lowlevel filter`
- feat(YouTube/Translations): update translation
`Arabic`, `Brazilian`, `Chinese Traditional`, `French`, `German`, `Greek`, `Indonesian`, `Italian`, `Japanese`, `Korean`, `Polish`, `Romanian`, `Russian`, `Spanish`, `Turkish`, `Ukrainian`, `Vietnamese`


YouTube Music
==
- feat(YouTube Music): add support version `v6.23.54`
- fix(YouTube Music/Remember playback speed): change default value
- feat(YouTube Music/Translations): update translation
`Indonesian`, `Polish`, `Russian`


Etc
==
- build: bump dependencies
- When updating from YouTube v18.33.40 or lower to YouTube v18.34.xx or later, a clean install is recommended.


※ Compatible ReVanced Manager: [RVX Manager v1.13.1 (fork)](https://github.com/inotia00/revanced-manager/releases/tag/v1.13.1)
[Crowdin translation]
- [YouTube/European Countries](https://crowdin.com/project/revancedextendedeu)
- [YouTube/Other Countries](https://crowdin.com/project/revancedextended)
- [YT Music](https://crowdin.com/project/revanced-music-extended)

---
CLI: j-hc/revanced-cli-4.0.2-all.jar  
Integrations: ReVanced/revanced-integrations-0.120.0.apk  
Patches: ReVanced/revanced-patches-2.195.0.jar  

### [2.195.0](https://github.com/ReVanced/revanced-patches/compare/v2.194.0...v2.195.0) (2023-10-20)
### Bug Fixes
* Indent option description correctly ([d4a9ea1](https://github.com/ReVanced/revanced-patches/commit/d4a9ea1f6c7ab9d25fd60695cce0965c7b5269a4))
* **Reddit - Sanitize sharing links:** Restore compatibility with newer versions of the app ([1671d8d](https://github.com/ReVanced/revanced-patches/commit/1671d8d826a08273fae5ccffc4a4ebfef9648fe2))
* **YouTube - Hide layout components:** Hide new channel watermark component ([cbfd569](https://github.com/ReVanced/revanced-patches/commit/cbfd5691d31ed144eac1d23de918ab5a6a905dfa))
### Features
* **YouTube - Theme:** Disable gradient loading screen ([90d5877](https://github.com/ReVanced/revanced-patches/commit/90d5877950095b7abacdca979bc7ad709192eee2))
* **YouTube:** Add `Announcements` patch ([#3166](https://github.com/ReVanced/revanced-patches/issues/3166)) ([f977983](https://github.com/ReVanced/revanced-patches/commit/f97798391ffc3477f781d43817664d31cfcd209a))
* **YouTube:** Add `Spoof device dimensions` patch ([c8d409e](https://github.com/ReVanced/revanced-patches/commit/c8d409e1dbda6ac45fef01912ce7afad1022b4b7))

---  
