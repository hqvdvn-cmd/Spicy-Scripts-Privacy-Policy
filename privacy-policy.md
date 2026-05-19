# Spicy Scripts Privacy Policy

Effective date: 2026-05-18

Spicy Scripts is a Chrome extension for saving reusable message scripts, using Smart Paste, and scheduling messages in Fansly chats.

## Data Processed by the Extension

Spicy Scripts may process the following data when you use the extension:

- Saved script folders, script titles, and script message text.
- Extension settings, including theme, timer delay, and Smart Paste speed.
- Scheduled message data, including message text, script title, send time, Fansly chat URL, Fansly chat ID, and visible fan display name.
- Clipboard text, only when you use Smart Paste from the context menu or keyboard shortcut.
- Fansly message composer content, only to insert, type, verify, or schedule the message you requested.
- Local extension logs used for debugging. Logs may include event names, timestamps, error messages, chat identifiers, fan display names, and message length. Logs do not intentionally store full message text.
- Timer notification content, including a short local preview of the scheduled message, may be shown by Chrome when a timer fires.

## How Data Is Stored

All extension data is stored locally in the user's browser using Chrome extension storage (`chrome.storage.local`) and Chrome alarms for scheduled sends.

Spicy Scripts does not operate a remote server, does not upload user messages, and does not sell or share user data with third parties.

## How Data Is Used

The extension uses local data only to provide its core features:

- Display saved scripts in the extension popup.
- Insert or type selected text into the Fansly message composer.
- Read clipboard text when the user explicitly triggers Smart Paste.
- Schedule a message for a specific Fansly chat while that chat tab remains available.
- Restore extension settings such as theme, timer delay, and typing speed.
- Troubleshoot extension behavior through local logs.

## Chrome Permissions

Spicy Scripts requests these permissions:

- `storage`: saves scripts, folders, settings, timers, and local logs in Chrome storage.
- `tabs`: finds the active Fansly chat tab and sends commands to the correct tab.
- `alarms`: schedules timed message sends.
- `contextMenus`: adds Smart Paste actions to the normal right-click menu in Fansly message fields.
- `scripting`: injects the content script again if Chrome unloads it or the tab needs reconnection.
- `notifications`: shows a local Chrome notification when a scheduled timer fires, succeeds, or cannot be sent.
- `clipboardRead`: reads clipboard text only after the user explicitly triggers Smart Paste.
- `clipboardWrite`: supports copying saved scripts to the clipboard.
- `activeTab`: allows interaction with the active tab after user action.
- Host access to `https://fansly.com/*` and `https://*.fansly.com/*`: allows the extension to find the Fansly composer, insert text, click send, and read the active chat context for timers.

## Data Sharing

Spicy Scripts does not transmit user data to external servers.

The extension does not use analytics, advertising SDKs, tracking pixels, or third-party data processors.

## Data Retention and Deletion

Data remains stored locally until the user deletes it, imports a replacement backup, clears browser extension data, or uninstalls the extension.

Uninstalling the extension removes its Chrome extension storage data.

## User Control

Users can:

- Edit or delete saved scripts from the extension popup.
- Cancel active timers.
- Export or import local backups.
- Clear extension data by removing the extension from Chrome.

## Contact

For support or privacy questions, contact the developer using the support email provided in the Chrome Web Store listing.
