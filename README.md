# SHIV Media Editor (Android & Web)

[![Build Android APK](https://github.com/shivamgupt-2010/shiv-media-editor/actions/workflows/build-apk.yml/badge.svg)](https://github.com/shivamgupt-2010/shiv-media-editor/actions/workflows/build-apk.yml)

**SHIV Media Editor** is a professional-grade, AI-powered multimedia creative suite for Android and Web. Built under the SHIV brand philosophy: **One application. Complete creative freedom. SHIV AI integration.**

---

## 🌟 Studios Included

1. **Authentication First**:
   - Mandatory sign-in and account registration via SHIV Identity.
   - Biometric quick-unlock support and local session persistence.
2. **Video Studio**:
   - Multi-track timeline (Video, B-Roll, Audio, Subtitles, FX).
   - Dynamic aspect ratio switcher (16:9 Landscape, 9:16 Reels/Shorts, 1:1 Square).
   - Colorkey background removal (green screen / magenta key).
   - Real-time filters and cinematic LUTs (Teal & Orange, Cyberpunk, Film Grain, Noir).
3. **Photo Studio**:
   - AI Subject isolation & background eraser (transparent PNG export).
   - Touch canvas adjustments: brightness, contrast, saturation.
   - Text & watermark stamping.
4. **Audio Studio**:
   - Dynamic waveform analyzer powered by Web Audio API.
   - Edge-TTS Neural voiceover generation.
   - Cinematic sound effects soundboard (whoosh, sub bass drop, glitch, riser).
5. **Motion Graphics**:
   - Keyframe typography, cyber lower-thirds, logo reveal bursts.
6. **Templates & Creative Marketplace**:
   - Pre-designed editable templates for Reels, Shorts, YouTube intros, and Instagram ads.
7. **SHIV AI Native Copilot**:
   - Natural language commands: "Remove background", "Make cinematic reel", "Add voiceover".

---

## 🚀 Building & Installing APK

### Automatic CI/CD via GitHub Actions
Every push to `main` automatically runs `./gradlew assembleDebug`, publishes release artifacts, and generates installable `.apk` packages under [Releases](https://github.com/shivamgupt-2010/shiv-media-editor/releases).

### Local Build
```bash
./gradlew assembleDebug
adb install -r app/build/outputs/apk/debug/app-debug.apk
```
