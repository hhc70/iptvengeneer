# IPTV Player Android App

A modern dark-theme IPTV player scaffold for Android phone, tablet, and Android TV.

## Included features

- M3U playlist loading from URL
- M3U playlist loading from a local file
- Channel list UI with search
- Video playback with Jetpack Media3 ExoPlayer
- Favorite channels saved with DataStore
- Android TV launcher support and D-pad-friendly rows
- Picture-in-picture enabled on supported Android versions/devices
- Clean Compose-based dark UI

## Tech stack

- Kotlin
- Jetpack Compose
- Jetpack Media3 ExoPlayer
- Preferences DataStore

## Notes

- This scaffold focuses on live IPTV playback and playlist browsing.
- Some IPTV providers use stream formats, headers, DRM, or authentication flows that need extra player configuration.
- TV PiP availability depends on Android/Google TV version and device support.

## Next improvements you may want

- EPG support
- Logo loading with Coil
- Channel grouping tabs
- Recent channels
- MediaSession integration
- Robust stream error handling and retry
- Dedicated TV-only layout with larger cards
- HLS/DASH specific tuning
