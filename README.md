# 📞 Spontaneity Is Calling

A native Android app built with **Kotlin** and **Jetpack Compose** that triggers a fake incoming call from **" العفوية "** via hardware gestures and shortcuts to gracefully save you from bad jokes.

---

## 💡 Overview

Have you ever sat through a joke so dry and forced that someone said: *"Spontaneity is calling you from the hospital"*?

**Spontaneity Is Calling** turns that iconic response into a physical reality. Built natively for Android using Kotlin, the app listens for hardware gestures (like double-tapping the back of your phone) to immediately display a full-screen incoming call interface from **"Spontaneity"** (العفوية).

Answer the call, put it on speaker, and let "Spontaneity" play a hilarious pre-recorded message in real-time.

---

## ✨ Features

* 📱 **Jetpack Compose Call UI:** Modern, reactive full-screen incoming call screen designed to match native Android Material 3 guidelines.
* ⚡ **Low-Latency Sensor Detection:** Uses Android's native `SensorEventListener` to catch back-tap gestures with high precision and zero bridge latency.
* 🔄 **Foreground Service Daemon:** Runs a lightweight background service to trigger the fake call screen even when the app is closed or the screen is locked.
* 🔊 **Native MediaPlayer Support:** High-performance playback of ringtones, haptic vibration patterns, and satirical voice notes upon answering.
* 🎛️ **Customization & Localization:** Full control over caller avatar, contact name, custom voice recordings, and Arabic/English language support.

---

## 🛠️ Tech Stack

* **Language:** Kotlin
* **UI Framework:** Jetpack Compose & Material 3
* **Hardware Sensors:** Android `SensorManager` & `Accelerometer API`
* **Background Processing:** Android `ForegroundService` & `WorkManager`
* **Audio Engine:** Android `MediaPlayer` / `SoundPool`
* **Build System:** Gradle (Kotlin DSL)

---

## 🗺️ Development Roadmap

### Phase 1: Native Call UI (Jetpack Compose)
- [x] Design Full-Screen Incoming Call Activity with Jetpack Compose.
- [x] Implement Accept, Decline, and Audio playback state logic.
- [ ] Configure System Overlay permissions (`SYSTEM_ALERT_WINDOW`) for pop-up triggers.

### Phase 2: Sensor & Service Infrastructure
- [ ] Implement native `SensorEventListener` algorithm for back-tap gesture recognition.
- [ ] Build robust `ForegroundService` for persistent background detection.
- [ ] Map physical volume hardware key shortcut receiver.

### Phase 3: Customization & Polish
- [ ] Add Settings Screen to allow custom voice clip recording & caller profile edits.
- [ ] Multi-language support (Arabic & English UI strings).

---

## 🚀 Build & Run (Linux Environment)

### Prerequisites

* **Android Studio** (Jellyfish or newer) installed on Linux.
* **Android SDK** (API Level 34+).

### Instructions

1. **Clone the repository:**
   ```bash
   git clone [https://github.com/your-username/spontaneity-calling.git](https://github.com/your-username/spontaneity-calling.git)
