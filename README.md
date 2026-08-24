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

Screenshots demonstrating the behavior will be available in the `evidence/` directory.

## Notes

The issue is reproducible on WhatsApp Business version 2.26.32.79 running on a OnePlus 7T with Android 12.
