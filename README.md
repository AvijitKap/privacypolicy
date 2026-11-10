# Privacy Policy for FocusFeed

**Effective Date:** November 10, 2026  
**App Name:** FocusFeed (Package: `com.crackeddev.focusfeed`)  
**Developer:** CrackedDev  

## 1. Overview
FocusFeed ("the App"), developed by CrackedDev ("we", "our", or "us"), is a productivity and screen-time management application designed to help users block distracting short-form content and notifications during active focus sessions. 

We are committed to protecting your privacy. **All screen detection, app blocking, and notification filtering occur 100% locally on your device. We do not operate external servers to collect, store, transmit, share, or sell your personal or sensitive usage data.**

---

## 2. Sensitive Permissions & API Disclosures

To function as an effective focus and distraction-blocking tool, FocusFeed requires your explicit consent to use two high-privilege Android system services. Below is an exact disclosure of how these services operate and how your data is handled:

### A. AccessibilityService API (`android.permission.BIND_ACCESSIBILITY_SERVICE`)
* **Why we request it:** FocusFeed uses the Android AccessibilityService API strictly to enforce your user-configured focus sessions and prevent session circumvention.
* **What it detects:** During an active focus session, the service monitors foreground package names and window/view hierarchy identifiers solely to detect:
  1. **YouTube Shorts** interfaces within the YouTube app.
  2. **Instagram** (including Instagram Reels and feed screens).
  3. **Application uninstall and force-stop system screens** targeting FocusFeed while a locked focus timer is actively running.
* **How data is processed:** All screen event inspection happens **100% locally and ephemerally in real-time memory on your device**. FocusFeed does not read, log, capture, save, or transmit your personal messages, passwords, keystrokes, browsing history, or screen text to any external server or third party.

### B. NotificationListenerService API (`android.permission.BIND_NOTIFICATION_LISTENER_SERVICE`)
* **Why we request it:** FocusFeed uses the NotificationListenerService API to prevent notification distractions while you are working or studying.
* **What it detects:** During an active focus session, the service checks the originating package name of incoming notifications solely to identify and suppress notifications from **Instagram**.
* **How data is processed:** Notification metadata is evaluated **locally on your device in real time**. FocusFeed never reads, stores, logs, or transmits the content of your notifications, messages, or contacts.

---

## 3. Subscriptions & In-App Payments
* **Google Play Billing:** FocusFeed offers optional paid subscriptions and in-app purchases processed exclusively through the **Google Play Billing API**.
* **No Financial Data Collected by Us:** When you make a purchase, the transaction is handled directly by Google Play. CrackedDev never receives, processes, or stores your name, email address, credit/debit card details, UPI ID, or billing address.
* **Subscription Verification:** FocusFeed communicates with the Google Play Store client on your device only to verify anonymous purchase tokens and subscription status (active/expired) so that Pro features can be unlocked.
* For more details on how Google handles payment information, please refer to the [Google Privacy Policy](https://policies.google.com/privacy).

---

## 4. Data Collection, Storage, and Sharing
* **Personal Data:** We do not require account registration and do not collect your name, email address, phone number, location, or personal identifiers.
* **App Preferences:** Your focus session timers, blocklist settings, and usage statistics are stored strictly locally on your device using standard Android local storage.
* **Third-Party Sharing:** Zero personal, screen, or notification data ever leaves your device or is shared with third parties, advertisers, or analytics providers.

---

## 5. User Control & Revoking Permissions
You have full control over the permissions and subscriptions associated with FocusFeed at any time:
1. **Revoke Accessibility Access:** Go to your device's **Settings -> Accessibility -> Installed Apps (or Downloaded Services) -> FocusFeed** and toggle the service off.
2. **Revoke Notification Access:** Go to your device's **Settings -> Notifications -> Notification access (or Device & app notifications) -> FocusFeed** and toggle access off.
3. **Manage or Cancel Subscriptions:** You can view, manage, or cancel your subscription at any time through the **Google Play Store app -> Profile Icon -> Payments & subscriptions -> Subscriptions -> FocusFeed**.
4. **Data Deletion:** Because all app preferences and timer configurations are stored locally on your device, clearing the app's storage or uninstalling FocusFeed permanently and immediately deletes all local data associated with the App.

---

## 6. Changes to This Privacy Policy
We may update this Privacy Policy from time to time to reflect changes in app functionality or Google Play policy requirements. Any updates will be posted to this URL with an updated "Effective Date."

---

## 7. Contact Us
If you have any questions or concerns regarding this Privacy Policy or FocusFeed's privacy practices, please contact us at:
* **Developer:** CrackedDev
* **Email:** [Insert Your Support Email Address Here]
