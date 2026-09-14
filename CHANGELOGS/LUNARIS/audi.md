## Lunaris AOSP v3.12

**Status:** Unofficial

**Security Patch:** September 2026

**Maintainer:** SathiyaSenpai

### Changelog
**Date:** 14/09/2026
- Device: Inherit LinkToWindows
- Device: Enable VoNR support
- Device: Fix Type-C headset mic not working in calls and recordings
- Device: Fix rare, random Bluetooth failures
- Device: Optimize UI rendering and caching for smoother scrolling and animations
- Device: Fix PowerHAL initialization not triggering on boot
- Device: Fix stutters during screen recording and casting
- Device: Clean up duplicate system properties across partitions
- Merge September security patch
- Merge Upstream changes
- Drop messy blur algorithm changes
- update NOSAtmosphereEffect
- Other miscellaneous improvements

**Date:** 01/09/2026
- Device: Fix fingerprint sensor not working when display turned off
- Device: Improve auto-brightness 
- Device: Fix WiFi taking 10-15 seconds to turn on
- Fix charging animation flashing briefly after unlock
- Reduce transition boost duration
- Merge with upstream

**Date:** 17/08/2026

* audi: Fix HDR brightness level (Imported displayconf from AOSPA which is taken from (pdx256))
* audi: Enable Bypass charging support
* audi: Enable support for Reality display engine
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

**Date:** 07/08/2026

* Android 16 Stable for the initial release.
* Merged the August 2026 security patch.
* Integrated Dolby audio support.
* Added Basic Call Recorder (BCR).
