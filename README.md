<div align="center">
  <img src="logo.jpg" alt="NotAudible Logo" width="220" style="border-radius: 24px;" />

  # NotAudible
  **Free open-source multilingual audiobook streaming player for Android without ads, subscriptions, or DRM**

  [![Kotlin](https://img.shields.io/badge/Kotlin-2.0-FF8C00?style=for-the-badge&logo=kotlin&logoColor=white)](https://kotlinlang.org/)
  [![Jetpack Compose](https://img.shields.io/badge/Jetpack%20Compose-Material%203-FF8C00?style=for-the-badge&logo=jetpackcompose&logoColor=white)](https://developer.android.com/jetpack/compose)
  [![Media3 ExoPlayer](https://img.shields.io/badge/Media3-ExoPlayer-11131A?style=for-the-badge&logo=android&logoColor=FF8C00)](https://developer.android.com/media/media3)
  [![Telegram](https://img.shields.io/badge/Telegram-@K1IR2I3L4L5-2AABEE?style=for-the-badge&logo=telegram&logoColor=white)](https://t.me/K1IR2I3L4L5)
</div>

---

## Features

- **9 Audible Language Regions:** Full interface and catalog localization for Russian, English, German, French, Italian, Spanish, Japanese, Portuguese, and Simplified Chinese.
- **Two Recommendation Formats ("For You"):** Classic endless feed and full-screen vertical swipe shorts stream.
- **Smart Search with Typo Protection:** Automatic spelling correction (Yandex Speller API + Fuzzy Levenshtein search) and keyboard layout mismatch recognition.
- **Precise Auto-Save Progress:** Remembers exact chapters and seconds on pause, book switching, or app closure.
- **Background Play & Lock Screen:** System `MediaSessionService` with notification shade controls and bluetooth/headset support.
- **Offline Mode:** Download individual chapters or entire books directly to internal device storage.
- **Advanced Audiobook Tools:**
  * Smart auto-rewind 5 seconds back after long pauses.
  * Sleep timer (15 / 30 / 60 minutes or end of current chapter).
  * Hardware audio boost for quiet recordings (`Audio Boost` up to `+12 dB`).
  * Bookmarks with custom text notes by timestamps.
  * Switch between alternative narrators for the same book.

---

## Installation

1. Go to the **[Releases](../../releases/latest)** section.
2. Download the latest **`NotAudible-v1.0.apk`** file to your Android smartphone and install it.

---

## Building from Source

1. Clone the repository:
   ```bash
   git clone [https://github.com/K1IR2I3L4L5/NotAudible.git](https://github.com/K1IR2I3L4L5/NotAudible.git)
1. Open the project folder in Android Studio.
2. Wait for the Gradle sync to finish and click Run (▶).

Contacts & Author
Developer: https://t.me/K1IR2I3L4L5
