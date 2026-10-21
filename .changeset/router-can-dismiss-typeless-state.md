---
'expo-router': patch
---

Fix `router.canDismiss()` returning `false` in an anchored stack opened from a deep link, and warn when a non-stack navigator uses `unstable_settings.anchor`.
