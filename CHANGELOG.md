0.3.2 (Oct 17 2015)
-------------------

* Backend robustness fixes, drop duplicates and other invalid messages.
* Fix lockup in sign-up page if button is pressed more than once.
* Small UI fixes.

0.3.1 (Oct 12 2015)
------------------

* Add group update and group leave functionality.
* Use multiple dialog bubble colors.
* Stop offering sending random files as attachments, Android does not support it.
* Allow sending contact phone numbers as attachments.
* Bugfixes.

0.3.0 (Oct 5 2015)
-------------------

* Persist conversations by saving sessions to SQLite and attachments to files.
  Storage is bound to change format and is currently unencrypted.
  Things may get lost on upgrades until it stabilizes.
* Improved group messaging.
* Allow resetting the session (to debug or to get rid of corrupted sessions).
* Support sending and playback of audio attachments.
* Add session search.
* Show send timestamps instead of receive timestamps on messages and sessions.

0.2.6 (Sep 25 2015)
------------------

 * Errors no longer require an app restart but are presented in a dialog.
 * Fix outgoing timestamp that was in the very distant future.
 * Fix the contact search field.
 * Fix group member selection.
 * Fix avatars in group chats.
 * Do not allow sending attachments larger than 100 Mib to prevent OOM.
 * Add group info dialog.
 * Add message info dialog when one message is selected to show timestamps.
 * Add welcome page to run on app start.

0.2.5 (Sep 22 2015)
------------------

 * Make sending messages asynchronous, so they don't block the UI.
 * Show sending/sent/delivered status on outgoing messages.
 * Handle network disconnections.

0.2.4 (Sep 18 2015)
------------------

 * Allow sending attachments in group messages.
 * Show thumbnails for image attachments.

0.2.3 (Sep 11 2015)
------------------

 * Stop encrypting the session metadata and asking for an encryption password.
   This follows the Android app's decision, and is needed for cross-device sync
   in the future.

0.2.2 (Sep 8 2015)
------------------

 * Initial incomplete group messaging support.
 * Show app version in settings.
 * Fix crash introduced in 0.2.1

0.2.1 (Sep 8 2015)
------------------

 * Handle contacts with multiple phone numbers.

0.2.0 (Sep 4 2015)
------------------

 * Get address book contacts via the content hub instead of the DBus service
   so it can be published in the app store.
 * Show per user color avatars.
 * Fix app icon size to look better in the app scope.

0.1 (Aug 13 2015)
---

 * Initial public release.
