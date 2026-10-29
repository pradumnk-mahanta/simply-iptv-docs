# Privacy Policy for Simply IPTV

**Effective Date:** October 29, 2026  
**Last Updated:** October 29, 2026  

Simply IPTV ("we," "our," or "us"), developed by **Pradumn Mahanta** (Application ID: `win.itryto.simplyiptv`), is committed to protecting your privacy. This Privacy Policy describes how Simply IPTV handles user information when you use our Android TV application.

---

### 1. Overview & Core Philosophy

Simply IPTV is a client-side media player designed for Android TV and Google TV devices. Our core privacy philosophy is simple: **we do not collect, harvest, store, or sell your personal information.** Your data, playlists, and preferences stay on your device.

---

### 2. Information We Do NOT Collect

*   **No Personal Identification Information (PII):** We do not require you to create an account, register, or provide personal details such as your name, email address, physical address, or phone number.
*   **No Server-Side Tracking or Analytics:** Simply IPTV does not transmit your playlist URLs, channel viewing history, favorite channels, or watch time to any developer-operated servers.
*   **No Advertising Identifiers or Trackers:** The application does not contain advertising SDKs, ad brokers, or third-party behavioral analytics trackers.

---

### 3. Data Handled Locally on Your Device

All configurations and settings are stored strictly **locally on your device** using Android Room Database and Android Jetpack DataStore:

*   **Playlist URLs (M3U / M3U8):** URLs and channel lists you configure are stored locally on your device to enable channel navigation and playback.
*   **EPG Guide Data (XMLTV):** Program guide URLs and cached TV guide programs are stored locally in the device's internal SQLite database.
*   **User Preferences & Favourites:** Settings such as theme (Light/Dark), UI interactions, favorite channel keys, and last-watched channel state remain strictly local.
*   **Android TV "Continue Watching" / "Watch Next":** Channel shortcuts and locally generated 16:9 banner images published to the Android TV system launcher are stored locally on your device and communicated solely to Android TV's system provider (`TvContractCompat`).

You may completely erase all locally stored data at any time by clearing the app data in Android TV **Settings > Apps > Simply IPTV > Clear data**, or by uninstalling the app.

---

### 4. Network Connections & Third-Party Media Streaming

*   **Direct Media Streaming:** When you initiate playback of a channel or stream, your device establishes a direct network connection with the third-party server hosting that stream (as defined in your playlist). Simply IPTV acts purely as a player client; we do not proxy, intercept, record, or route your stream traffic through our servers.
*   **Third-Party Privacy Practices:** Streaming servers and EPG providers specified in your playlists operate under their own independent privacy terms. We encourage you to review the privacy policies of any third-party IPTV service providers you use.

---

### 5. In-App Subscriptions & Billing Data

*   **Google Play Billing:** Simply IPTV offers an optional Premium subscription. All payment transactions, credit card processing, billing inquiries, and subscription renewals are handled exclusively by the **Google Play Store** via Google Play Billing.
*   **Developer Access:** We never receive, process, or store your payment card numbers, billing addresses, or banking information. Google Play provides only cryptographically signed purchase tokens and entitlement status to verify your subscription state.

---

### 6. Android Permissions Used

Simply IPTV requests only permissions necessary for core media player functionality:

*   `INTERNET`: Required to connect to user-provided stream URLs and download EPG XMLTV guides.
*   `ACCESS_NETWORK_STATE`: Required to monitor network connectivity and provide informative player status when network connections drop.
*   `RECEIVE_BOOT_COMPLETED`: Required to reschedule periodic background playlist and EPG refreshes if scheduled by the user via WorkManager.
*   `FOREGROUND_SERVICE` & `FOREGROUND_SERVICE_MEDIA_PLAYBACK`: Required to maintain smooth, uninterrupted audio/video playback and media session metadata integration with Android TV.
*   `BILLING`: Required to enable Google Play Billing for in-app subscriptions.

---

### 7. Children's Privacy

Simply IPTV does not target or knowingly collect information from children under the age of 13 (or under the applicable age of digital consent in your jurisdiction). The app is a general-purpose media utility with zero personal data collection.

---

### 8. Changes to This Privacy Policy

We may update this Privacy Policy periodically to reflect new app features, technical adjustments, or legal obligations. Any updates will be published with a revised "Last Updated" date at:
[https://github.com/pradumnk-mahanta/simply-iptv-docs](https://github.com/pradumnk-mahanta/simply-iptv-docs)

---

### 9. Contact Us

If you have any questions, feedback, or concerns regarding this Privacy Policy or your privacy while using Simply IPTV, please contact us at:

*   **Email:** [support@itryto.win](mailto:support@itryto.win)
*   **Issue Tracker & Documentation:** [https://github.com/pradumnk-mahanta/simply-iptv-docs](https://github.com/pradumnk-mahanta/simply-iptv-docs)
*   **Developer:** Pradumn Mahanta

