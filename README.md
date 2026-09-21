# GOAT Holidays CRM Android App

Android WebView app for:

`https://crm.goatholidays.in/login`

## Based on the supplied reference app

This project keeps the same single-WebView architecture and mobile behaviour as the supplied Odyssey CRM Android reference, rebranded and configured for GOAT Holidays CRM.

## Included

- Direct GOAT Holidays CRM login launch
- CRM login cookies/session retained
- Mobile responsive WebView; no forced desktop mode
- File upload support
- Normal CRM downloads and generated blob/data PDF downloads
- Phone, email, intent and external app links
- Android Back navigates CRM WebView history
- Network error panel with Retry
- Geolocation permission support for CRM attendance/location features
- Adaptive GOAT Holidays launcher icon
- WebView cache is cleared once after each app version update while cookies remain intact

## Android configuration

- Package / Application ID: `in.goatholidays.crm`
- Minimum Android: API 24 (Android 7.0)
- Target Android: API 35
- Version: `1.0.0`

## Build APK with GitHub Actions

1. Upload this project to the root of a GitHub repository.
2. Open **Actions** > **Build Android APK**.
3. Run the workflow.
4. Download artifact **GOAT-Holidays-CRM-APK**.
5. Extract `app-debug.apk`.

The workflow also runs on pushes to `main`.

## Main CRM URL

Defined in:

`app/src/main/java/in/goatholidays/crm/MainActivity.java`
