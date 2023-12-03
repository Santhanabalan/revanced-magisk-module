YouTube: 18.48.37  
YouTube-Extended: 18.48.37  
Music-Extended (arm64-v8a): 6.29.57  
Music-Extended (arm-v7a): 6.29.57  
Music (arm64-v8a): 6.29.57  
Music (arm-v7a): 6.29.57  

Install [Vanced Microg](https://github.com/TeamVanced/VancedMicroG/releases) for non-root YouTube or YT Music  

[revanced-magisk-module](https://github.com/Santhanabalan/revanced-magisk-module)  

---
Changelog:  
CLI: inotia00/revanced-cli-4.3.1-all.jar  
Integrations: inotia00/revanced-integrations-0.124.12.apk  
Patches: inotia00/revanced-patches-2.201.12.jar  

YouTube
==
- feat(YouTube): add support version `v18.46.43`
- feat(YouTube): add `Hide voice search button` patch
- feat(YouTube/Hide comment component): add `Hide create shorts button` settings [Screenshot](https://imgur.com/a/9u0vKM1)
- feat(YouTube/Hide general ads): add `Close interstitial ads` settings (untested, example for `interstitial ads` - https://github.com/inotia00/ReVanced_Extended/issues/1190)
- fix(YouTube): `Force fullscreen` patch fails on some versions https://github.com/inotia00/ReVanced_Extended/issues/1766
- fix(YouTube/Hide layout components): `Hide feed surveys` sometimes does not work
- fix(YouTube/Settings): some translations are wrong https://github.com/inotia00/ReVanced_Extended/issues/1767
- fix(YouTube/SponsorBlock): some videos refused to end where there's a skippable segment at the end https://github.com/inotia00/ReVanced_Extended/issues/1745
- fix(YouTube/Swipe controls): swipe gesture working even after using `Lock screen` feature when `Press-to-swipe` is enabled
- feat(YouTube/Translations): update translation
`Arabic`, `Brazilian`, `French`, `Greek`, `Indonesian`, `Italian`, `Korean`, `Polish`, `Russian`, `Spanish`, `Turkish`, `Ukrainian`, `Vietnamese`


YouTube Music
==
- feat(YouTube Music): add `Hide voice search button` patch
- feat(YouTube Music/Hide music ads): add `Close interstitial ads` settings (untested, example for `interstitial ads` - https://github.com/inotia00/ReVanced_Extended/issues/1190)
- feat(YouTube Music/Translations): update translation
`Brazilian`, `Greek`, `Russian`


Etc
==
- when updating from YouTube v18.33.40 or lower to YouTube v18.34.xx or later, a clean install is recommended.

※ Compatible ReVanced Manager: [RVX Manager v1.17.1 (fork)](https://github.com/inotia00/revanced-manager/releases/tag/v1.17.1)
[Crowdin translation]
- [YouTube/European Countries](https://crowdin.com/project/revancedextendedeu)
- [YouTube/Other Countries](https://crowdin.com/project/revancedextended)
- [YT Music](https://crowdin.com/project/revanced-music-extended)

---
CLI: j-hc/revanced-cli-4.1.0-all.jar  
Integrations: ReVanced/revanced-integrations-0.125.0.apk  
Patches: ReVanced/revanced-patches-2.202.0.jar  

### [2.202.0](https://github.com/ReVanced/revanced-patches/compare/v2.201.1...v2.202.0) (2023-12-02)
### Bug Fixes
* **Spotify - Custom Theme:** Clarify patch option description ([#3338](https://github.com/ReVanced/revanced-patches/issues/3338)) ([1b9a90f](https://github.com/ReVanced/revanced-patches/commit/1b9a90f9753e40cb07e270e7f5144cd57c3c3ce3))
* **YouTube - Enable tablet layout:** Respect the original device layout ([cdbbe8f](https://github.com/ReVanced/revanced-patches/commit/cdbbe8f78d26f24e58362c7ef1da83bf689d52bb))
* **YouTube - Restore old seekbar thumbnails:** Move setting into 'Seekbar' submenu ([#3344](https://github.com/ReVanced/revanced-patches/issues/3344)) ([880091a](https://github.com/ReVanced/revanced-patches/commit/880091a96d1a628520732367c96c4c11fb93b72d))
### Features
* Modernize restart app logic ([#3343](https://github.com/ReVanced/revanced-patches/issues/3343)) ([3897647](https://github.com/ReVanced/revanced-patches/commit/3897647321b6c1860dc9804cac6c6985da8bb675))
* **YouTube:** Support version `18.45.43` ([#3345](https://github.com/ReVanced/revanced-patches/issues/3345)) ([ff82a36](https://github.com/ReVanced/revanced-patches/commit/ff82a36e6cd661201169246497176493d7093b58))

---  
