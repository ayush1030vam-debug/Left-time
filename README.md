# TimeLeft Android starter project

A minimal Kotlin Android app for a dark, purple-accented countdown with selectable date and time. The countdown shows days, hours, minutes, and seconds while the app is open, and can post a notification that may be shown on the lock screen.

## Important lock-screen limitation
Android apps cannot freely draw arbitrary live UI over the system lock screen. This starter uses a standard notification for lock-screen visibility. Notification content is not a second-by-second live display; the live seconds display runs while the app is open. Availability and appearance depend on Samsung lock-screen notification settings and One UI version.

## Build an APK
1. Install Android Studio on a computer.
2. Open this folder in Android Studio.
3. Allow Gradle sync and install any requested Android SDK platform (API 35).
4. Choose **Build > Build Bundle(s) / APK(s) > Build APK(s)**.
5. Android Studio will show the APK location. Transfer it to your Galaxy M33 and install it. You may need to allow installs from that source.

## Try it
- Launch TimeLeft.
- Enter an event name.
- Choose date and time.
- Tap **Save countdown**.
- Allow notifications when prompted.
- In Samsung Settings, allow TimeLeft notifications on the lock screen if you want to see the saved countdown there.

This is a starter project, not a prebuilt APK. It has not been compiled or tested on a physical Galaxy M33 in this environment.
