# App Details

## Changes

### Unreleased
- Fixing the false "Permissions Missing" popup on Android 10-12: `POST_NOTIFICATIONS` is only requested on Android 13+ (API 33), notification status is checked with `NotificationManagerCompat.areNotificationsEnabled()`, and SMS permission is checked separately.
- The settings redirect now only appears when a required permission is genuinely missing, and opens the notification settings page when notifications are turned off.

### 0.1.1
- Fixing app crash on some mobile GPU with kivymd 2.x . Thanks to [DorDeorz](https://github.com/DorDeorz) for the fix in [UniversalDownlaoder](https://github.com/DorDeorz/UniversalDownloader).

### 0.1.0
- App will check if required permissions are granted
- Adding logging for API requests
- Fixing the android bottom padding
- Adding a back button

### 0.0.1
- Initial version
