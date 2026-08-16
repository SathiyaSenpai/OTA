## Lunaris AOSP v3.12

**Status:** Unofficial

**Security Patch:** August 2026

**Maintainer:** SathiyaSenpai

### Changelog
**Date:** 17/08/2026

* avalon: Fix HDR brightness level (Imported displayconf from AOSPA which is taken from (pdx256))
* avalon: Enable Bypass charging support
* avalon: Enable support for Reality display engine
* sm8650: Allow surfaceflinger to use the big cluster
* sm8650: Import and reset perf boost configs to stock qcom values
* Improve and fix minor spoofing issue
* Improve QS Smoothness
* Introduce Custom QS scrim color
* Add blur background support in lockscreen widget
* Add dynamic island popup menu background style
* Remove gradient from IOS widget music player and dim background
* Change system dialog background color (Internet dialog, bt, etc..)
* Hide DynamicIsland chip while on lockscreen
* Make app launch animation faster
* Add 2 New Powermenu style
* Prevent DynamicIsland from overlapping statusbar icons
* Fix app close stutter
* Allow change QS widget order
* Limit max keygaurd chip size
* Fix waveform style renderer rounding
* Use MD3 font for keygaurd elements
* Tune QS clocks layout
* Redesign material QS widget player UI
* Allow change QS widget order
* Introduce WS widget utility box
* Implement Dot wave style pulse renderer
* Fix flicker on pulse hide transitions
* Switch back to stock interpolator for launcher animation

**Date:** 09/08/2026

* Add one time hotspot data limit
* Fix empty space when statusbar DynamicBar media disable
* Decouple DynamicBar keyguard music pill from statusbar media toggle
* Added user configuration for minimum and maximum fling velocity
* Fix Updater app Misconfigured

**Date:** 03/08/2026

* Removed the patch for dual sim 5G issue(Now its added in ROM Source)
* Fix notification count not being dismiss
* Dynamic Island implementation
* Allow hiding statusbar while capturing screenshots
* Remove broken app icon from statusbar lyric to restore empty space
* Synced with Latest Source

**Date:** 24/07/2026

* Synced with Latest Source
* Added a patch for dual sim 5G issue 

**Date:** 17/07/2026

* Improved Haptics and fixed no Vibration on Call

**Date:** 14/07/2026

* Dropped Lineage AIDL RichTap vibrator support
* Kang vibrator from 'pong'
* Merged latest android14-6.1-lts upstream updates
* Use lineage-libperfmgr for DT2W
* Adjusted SurfaceFlinger duration to 12.3ms for smoother rendering
* Removed obsolete OplusDoze
* Added optimized network configurations for Jio and Airtel
* Included oneplus IR
* Switched to LunarisDolby
* Fixed Widevine L1 HD streaming issues
* Added a shortcut option to restart SystemUI
* Merged the July 2026 security patch
* Enabled VOOC fast charging status on the lockscreen
* Other miscellaneous improvements


**Date:** 26/06/2026

* Android 16 Stable for the initial release.
* Merged the June 2026 security patch.
* Integrated Dolby audio support.
* Added Basic Call Recorder (BCR).
