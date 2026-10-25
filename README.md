# Waterly

**Drink water on a schedule that fits your day.**

Waterly is a small Android app that counts the glasses of water you drink and spreads the rest of your daily goal across the hours you are awake. It is built around a film-camera look: warm stock, a frame counter, and water that rises inside a viewfinder.

[Homepage](https://ixrrohitt.github.io/waterly/) · [Privacy policy](https://ixrrohitt.github.io/waterly/privacy.html) · [Download the APK](../../releases/latest)

---

## What it does

- **One tap per glass.** A glass is 220 ml by default (you can change both the glass size and the daily goal; the default goal is 4 L). A quick "Sure?" confirmation prevents accidental taps, and there is an undo.
- **A schedule built around your day.** On your first drink, Waterly asks when you will sleep. It spreads the remaining glasses between now and 45 minutes before bed, and re-plans after every glass.
- **Reminders you can't miss.** A notification at each drink time, with an "I drank" button. Turn on the loud alarm to play any audio file from your phone. The alarm stops when you press a volume key, tap Stop, tap "I drank", or open the app.
- **A daily streak.** One tap a day, once a day.
- **A resizable home-screen widget.** Log a glass or mark your streak without opening the app. The water in the widget moves. It switches to a compact layout when you shrink it.
- **Backups.** Save a file anywhere (Google Drive's picker works) and load it back later, or connect Google Drive for automatic backups. See [Google Drive backup](#google-drive-backup).

## Install

1. Open the [latest release](../../releases/latest) on your phone and download `app-release.apk`.
2. Open the file. Android will ask you to allow installs from your browser or file manager; allow it for this one install.
3. Google Play Protect may warn that the developer is unknown. That is expected for an app installed outside the Play Store.
4. On first launch, allow notifications. On phones that aggressively kill background apps (Xiaomi, Realme, Vivo and similar), set the app's battery mode to **Unrestricted** and turn on **Autostart** so reminders arrive on time.

Requires **Android 9 (API 28)** or newer.

## Google Drive backup

Backups go to a hidden folder in your own Drive that only Waterly can open. Waterly asks for the `drive.appdata` permission and nothing else.

- It needs **Google Play Services** on the phone. Phones without Google apps can use the file backup instead.
- The OAuth consent screen is currently in *Testing* mode, so Drive sign-in works only for Google accounts that have been added as test users. File backup works for everyone.

## Privacy

Everything Waterly records stays on your phone. There is no account, no server, no analytics and no ads. The only time data leaves the device is when you choose to back it up to your own Google Drive. Full details are in the [privacy policy](https://ixrrohitt.github.io/waterly/privacy.html).



## Credits

Made by [@ixrrohitt](https://github.com/ixrrohitt).
