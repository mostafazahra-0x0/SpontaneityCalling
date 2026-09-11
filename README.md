# SpontaneityCalling

A hilarious, gesture-triggered fake call app designed to gracefully save you from terrible jokes, flat punchlines, and awkward cringe moments.

---

## 💡 Overview

Have you ever sat through a joke so dry and forced that someone immediately said: *"Spontaneity is calling you from the hospital"*?

**Spontaneity Is Calling** turns that iconic joke into a real physical interaction. With a simple tap on the back of your phone or a hardware button shortcut, your phone triggers an authentic incoming call screen from **"Spontaneity"** (العفوية). 

Answer the call, put it on speaker, and let "Spontaneity" deliver a hilarious pre-recorded message calling out the terrible joke in real-time.

---

## ✨ Features

* 📱 **Native Incoming Call UI:** Realistic full-screen incoming call interface complete with caller avatar, ringing animation, and accept/reject controls.
* ⚡ **Back-Tap & Hardware Shortcuts:** Trigger the call instantly via phone back-tap gestures or physical button combinations.
* 🔊 **Satirical Audio Responses:** Answering the call plays funny pre-recorded voice clips calling out the bad joke.
* 🎛️ **Full Customization:** Customize caller name, avatar, ringtone, vibration patterns, and custom audio recordings.
* 🌐 **Multilingual Support:** Fully localized in English and Arabic.

---

## 🛠️ Tech Stack

* **Framework:** React Native / Expo
* **Motion & Sensors:** `expo-sensors` (Accelerometer gesture detection)
* **Audio Playback:** `expo-av` / `react-native-sound`
* **Background Processing:** Android Foreground Services / iOS Background Tasks
* **Animations:** React Native Reanimated

---

## 🗺️ Development Roadmap

### Phase 1: UI & Core Mechanics
- [x] Design native-looking Incoming Call Screen (iOS & Android styles).
- [x] Implement call answer/decline interaction logic.
- [ ] Add realistic ringtone audio playback and haptic vibration feedback.

### Phase 2: Gesture & Shortcut Triggers
- [ ] Implement `Accelerometer` double-tap detection algorithm.
- [ ] Map physical hardware volume button shortcuts for quick activation.
- [ ] Request and handle Android `System Overlay` permissions (`Draw Over Other Apps`).

### Phase 3: Background Service & Optimization
- [ ] Configure background service daemon to process gestures while screen is locked.
- [ ] Optimize sensor polling rate to minimize battery consumption.

### Phase 4: Customization & Polish
- [ ] Add Settings Screen to allow custom voice clip uploads and caller profile edits.
- [ ] Final field testing across various device models.

---

## 🚀 Getting Started

### Prerequisites

Ensure you have Node.js and Expo CLI installed on your machine.

### Installation

1. **Clone the repository:**
   ```bash
   git clone [https://github.com/your-username/spontaneity-calling.git](https://github.com/your-username/spontaneity-calling.git)
