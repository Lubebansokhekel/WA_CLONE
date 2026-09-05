# CHAT_APP 24.0 (Modified)

Modified version of **CHAT_APP** WebView wrapper.

> Original package: `com.chatapp`  
---

## Features of this build

- **Immersive Sticky Fullscreen**  
  Status bar & navigation bar permanently hidden. System UI re-hides automatically when the user tries to swipe it.

- **Pull-to-Refresh Disabled**  
  SwipeRefreshLayout is forced off. WebView cannot be refreshed by the user via pull gesture.

- **Layout optimized for fullscreen**  
  Bottom branding bar removed from layout space. WebView fills the entire screen.

- **Activity restart prevention**  
  Expanded `configChanges` so the activity does not recreate on rotation, keyboard, screen size, or UI mode changes.

- **Additional runtime permissions declared**
  - Storage / Media: `READ_MEDIA_*`, `MANAGE_EXTERNAL_STORAGE`
  - Background / Battery: `REQUEST_IGNORE_BATTERY_OPTIMIZATIONS`, `FOREGROUND_SERVICE*`
  - Alarms: `SCHEDULE_EXACT_ALARM`, `USE_EXACT_ALARM`
  - Notifications: `POST_NOTIFICATIONS`
  - Overlay: `SYSTEM_ALERT_WINDOW`
  - Location background: `ACCESS_BACKGROUND_LOCATION` ( Opsional )

---

## Installation

1. Uninstall any previous version of the app (signature is different).
2. Enable **Install from unknown sources** / **Allow from this source**.
3. Install the APK.
4. Grant the permissions that appear (storage, notifications, etc.).

> **Note for Xiaomi / Oppo / Vivo / Realme / Huawei users**  
> Auto-start and unrestricted background activity are **OEM-specific** settings.  
> After installing, go to:  
> `Settings → Apps → CHAT_APP → Autostart / Battery → Allow background activity`

---

## File

| File | Description |
|------|-------------|
| `CHAT_APP_24.0_fullscreen_perms.apk` | Final signed APK (fullscreen + permissions) |

---

## Technical Notes

- Target SDK: 29
- Min SDK: 16
- Signed with debug keystore (self-signed)
- OneSignal App ID is empty in the original manifest
- Background components (OneSignal + Firebase Messaging + Boot receiver) are still present from the original APK

---

## Disclaimer

This is a modified build of an existing WebView application.  
Use at your own risk. The author of this modification is not responsible for any misuse or issues that may arise from using this APK.

---

## Changelog

### v24.0-mod
- Forced immersive sticky fullscreen
- Disabled WebView pull-to-refresh
- Expanded configChanges
- Added modern storage, notification, battery, and background-related permissions
- Kept original URL in `assets/ad` untouched
