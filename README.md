# WhatsApp Business Android - Archived Chats Section Not Visible

> This is an independent bug reproduction report and is not affiliated with or endorsed by WhatsApp or Meta.

## Summary

WhatsApp Business for Android allows a chat to be archived, but after archiving the chat, the Archived section is not visible in the Android application.

The same archived chat remains accessible through WhatsApp Web using the same account.

## Environment

- Application: WhatsApp Business for Android
- App Version: 2.26.32.79
- Device: OnePlus 7T
- Model: HD1901
- Android Version: 12

## Steps to Reproduce

1. Open WhatsApp Business on Android.
2. Long-press any chat.
3. Select **Archive**.
4. Confirm that the chat disappears from the main chat list.
5. Return to the main Chats screen.
6. Look for an **Archived** section.
7. Observe that the Archived section is not visible.
8. Open WhatsApp Web using the same account.
9. Open **Menu → Archived**.
10. Observe that the archived chat is available there.

## Expected Behavior

The Android application should provide an Archived section that allows users to access and unarchive previously archived chats.

## Actual Behavior

The Android application successfully archives the chat, but the Archived section is not visible afterward.

The same archived chat is visible and accessible through WhatsApp Web.

## Cross-Platform Comparison

| Platform | Archive Chat | Access Archived Chats |
|---|---|---|
| WhatsApp Business Android | Yes | Not visible |
| WhatsApp Web | Yes | Yes |

## Evidence

### Android

#### WhatsApp Business App

<img src="evidence/01-whatsapp-business-app-page.jpeg" width="320">

#### WhatsApp Business Version

<img src="evidence/02-whatsapp-business-version.jpeg" width="320">

#### Device Environment

<img src="evidence/03-device-environment.jpeg" width="320">

#### Archived Section Not Visible

After archiving a chat, the Android main Chats screen does not show an **Archived** section.

<img src="evidence/07-android-main-screen-archived-section-not-visible.jpeg" width="320">

#### Chat Archived Successfully

The application confirms that the chat was successfully archived.

<img src="evidence/08-android-chat-archived-confirmation.jpeg" width="320">

#### Archived Option Not Available in Menu

The Android menu also does not provide an option to access archived chats.

<img src="evidence/09-android-menu-archived-option-not-visible.jpeg" width="320">

### WhatsApp Web

#### WhatsApp Web Main Screen

<img src="evidence/04-whatsapp-web-main-screen.png" width="850">

#### Archived Option Available

Unlike the Android application, WhatsApp Web provides an **Archived** option in the main menu.

<img src="evidence/05-whatsapp-web-archived-menu.png" width="850">

#### Archived Chats Accessible

The same archived chat is accessible from the **Archived** section on WhatsApp Web.

<img src="evidence/06-whatsapp-web-archived-section.png" width="850">

### Video Reproduction

The following screen recording demonstrates the issue on WhatsApp Business for Android.

[▶ Watch Android screen recording](evidence/10-android-archive-bug-reproduction.mp4)

[<img src="evidence/08-android-chat-archived-confirmation.jpeg" width="320" alt="Android archive bug video preview">](evidence/10-android-archive-bug-reproduction.mp4)


## Notes

The issue is reproducible on WhatsApp Business version 2.26.32.79 running on a OnePlus 7T with Android 12.
