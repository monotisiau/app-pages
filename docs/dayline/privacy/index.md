---
title: Dayline Privacy Policy
lang: en
---

[한국어](ko/)

# Dayline Privacy Policy

**Effective date:** September 3, 2026  
**App version:** 1.0.0  
**Package name:** studio.dayline.app

Dayline (the "App") is a productivity app that helps you view tasks and events in the flow of your day. This policy describes what information the App handles for Android version 1.0.0.

## 1. Summary

- The App **does not send user data to developer-operated servers.** It does not use account sign-in, advertising, or analytics SDKs.
- Todo data is stored in a **SQLite database on your device.**
- Device calendar events are read **read-only** when displayed; the App does not send them to servers or persist a separate copy.
- Reminder notifications are **scheduled and shown on your device only.**
- If Android automatic backup is enabled, app data (including todos) **may be included in Google account backup.**

## 2. Developer contact

- **App name:** Dayline
- **Contact:** [monoti.dev@gmail.com](mailto:monoti.dev@gmail.com)

For privacy-related questions, email us at the address above.

## 3. Information we process

The App uses information you enter or information already on your device. **None of the following is transmitted to developer-operated servers.**

### 3.1 Todo data

Todo information you enter in the App (for example title, date and time, completion status, reminder settings) is stored in a local SQLite database on your device.

### 3.2 Calendar events (read-only)

If you turn on calendar display and grant calendar access, the App reads calendar events stored on your device in **read-only** mode and shows them on the timeline.

- Events are read from the device each time they are displayed.
- The App **does not persist a local copy** of calendar events.
- The App **does not create, edit, or delete** calendar events.
- Read events are **not sent** to the developer or third parties.

Calendar access is requested when you open calendar display settings, not at app launch. You can use todo features without granting calendar access.

### 3.3 App settings

Settings such as which calendars to show (hidden calendar list) are stored on your device.

## 4. How we use information

| Information | Purpose |
|-------------|---------|
| Todo data | Show todos, mark completion, schedule reminders |
| Calendar events | Display events on timeline and calendar UI (read-only) |
| App settings | Remember your display preferences |

We do not use your data for purposes beyond those listed above.

## 5. Android permissions

The App requests the following permissions:

| Permission | Purpose |
|------------|---------|
| `POST_NOTIFICATIONS` | Show todo reminder notifications (Android 13+) |
| `SCHEDULE_EXACT_ALARM` | Fire reminders at the exact time you set |
| `READ_CALENDAR` | Read device calendar events for display (read-only) |
| `RECEIVE_BOOT_COMPLETED` | Restore scheduled reminders after device reboot |

If you deny a permission, related features (notifications, calendar display, etc.) may be limited; other features continue to work.

## 6. Third parties and international transfer

App 1.0.0 **does not provide** user data to third parties such as developer servers, ad networks, or analytics services.

If Android automatic backup (Google account backup) is enabled on your device, app data may be stored on Google infrastructure under Google's backup terms. That relationship is between you and Google; the Dayline developer does not directly access that backup.

## 7. Retention and deletion

- **Todos and settings:** Uninstalling the App removes its data from that device. Copies in Google account backup follow Google's backup settings and policies.
- **Calendar events:** Because the App does not store event copies, stopping display or uninstalling the App means the App no longer handles events. Original events remain in your device calendar app.

## 8. Children

The App is not directed at children under 13, and we do not knowingly collect personal information from children.

## 9. Security

Todo data stays on your device; the App does not include functionality to transmit that data over the network. Device lock and OS security updates depend on your device settings.

## 10. Changes to this policy

We may update this policy when features change or when required by law. Material changes will be communicated through app updates or this document (public URL). The **effective date** at the top will be updated.

## 11. Your rights

Because the App does not store personal information on developer servers, there is no server-side data to access, correct, or delete. You can edit or delete todos in the App and remove on-device data by uninstalling. Google backup copies can be managed in your [Google Account](https://myaccount.google.com/) settings.

Contact: [monoti.dev@gmail.com](mailto:monoti.dev@gmail.com)
