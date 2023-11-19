YouTube-Extended: 18.45.41  
Music-Extended (arm64-v8a): 6.28.52  
YouTube: 18.45.41  
Music-Extended (arm-v7a): 6.28.52  
Music (arm64-v8a): 6.28.52  
Music (arm-v7a): 6.28.52  
Instagram: 309.0.0.40.113  

Install [Vanced Microg](https://github.com/TeamVanced/VancedMicroG/releases) for non-root YouTube or YT Music  

[revanced-magisk-module](https://github.com/Santhanabalan/revanced-magisk-module)  

---
Changelog:  
CLI: inotia00/revanced-cli-4.1.1-all.jar  
Integrations: inotia00/revanced-integrations-0.121.7.apk  
Patches: inotia00/revanced-patches-2.196.7.jar  

YouTube
==
- feat(YouTube): add support version `v18.45.41`
- feat(YouTube): separate the `Hide channel profile components` patch from `Hide layout components` patch
- feat(YouTube/Hide channel profile components): add `Hide 'For You' shelf` settings https://github.com/inotia00/ReVanced_Extended/issues/1697
- feat(YouTube/Hide description components): add `Hide podcast sections` settings
- fix(YouTube/Enable wide search bar): even if `Enable Wide Search Bar` is turned off, the toolbar of You tab is replaced if `Enable wide search bar in you tab` is turned on
- fix(YouTube/Hide general ads): rollback legacy code
- fix(YouTube/Return YouTube Dislike): match to official ReVanced code
- fix(YouTube/Spoof player parameters): change response waiting time
- feat(YouTube/Translations): update translation
`Arabic`, `Chinese Traditional`, `French`, `Hungarian`, `Italian`, `Japanese`, `Korean`, `Polish`, `Russian`, `Spanish`, `Turkish`, `Ukrainian`, `Vietnamese`


YouTube Music
==
- feat(YouTube Music/Translations): update translation
`Chinese Traditional`, `Dutch`, `French`, `Japanese`, `Polish`, `Romanian`, `Russian`, `Turkish`, `Ukrainian`, `Vietnamese`


Etc
==
- build: bump dependencies
- when updating from YouTube v18.33.40 or lower to YouTube v18.34.xx or later, a clean install is recommended.


※ Compatible ReVanced Manager: [RVX Manager v1.15.1 (fork)](https://github.com/inotia00/revanced-manager/releases/tag/v1.15.1)
[Crowdin translation]
- [YouTube/European Countries](https://crowdin.com/project/revancedextendedeu)
- [YouTube/Other Countries](https://crowdin.com/project/revancedextended)
- [YT Music](https://crowdin.com/project/revanced-music-extended)

---
CLI: j-hc/revanced-cli-4.1.0-all.jar  
Integrations: ReVanced/revanced-integrations-0.122.0.apk  
Patches: ReVanced/revanced-patches-2.197.0.jar  

### [2.197.0](https://github.com/ReVanced/revanced-patches/compare/v2.196.0...v2.197.0) (2023-11-18)


### Bug Fixes

* **Nyx Music Plaer - Unlock pro:** Constrain to last working version ([96d24a3](https://github.com/ReVanced/revanced-patches/commit/96d24a3e2ef6bd323aa44a05aaf122683898e90a))
* **Remove screenshot restriction:** Improve reliability ([#2938](https://github.com/ReVanced/revanced-patches/issues/2938)) ([6b7cb7b](https://github.com/ReVanced/revanced-patches/commit/6b7cb7bd38348dbe4a56385356df6ed97e81c319))
* **YouTube - Client spoof:** Fix low resolution precise seeking thumbnails ([#3249](https://github.com/ReVanced/revanced-patches/issues/3249)) ([0cb41ef](https://github.com/ReVanced/revanced-patches/commit/0cb41efa067d74b873167718b25893cb2e1dd240))
* **YouTube - Disable resuming Shorts on startup:** Adjust patch name ([#3281](https://github.com/ReVanced/revanced-patches/issues/3281)) ([c332952](https://github.com/ReVanced/revanced-patches/commit/c3329527db739e6777fe8e77828e1226e4057b80))
* **YouTube - Hide layout components:** Reduce false positives when hiding mix playlists ([fb173e1](https://github.com/ReVanced/revanced-patches/commit/fb173e18afd5566a4ccdbb613810fa9646da9334))
* **YouTube - SponsorBlock:** Rename 
---  
