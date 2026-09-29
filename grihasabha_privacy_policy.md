# Privacy Policy for GrihaSabha (गृहसभा)

**Effective Date:** August 2026  
**Last Updated:** September 29, 2026  

---

## 1. Introduction & Overview

GrihaSabha (गृहसभा) ("we", "our", or "app") is a Housing Society & Gated Community Management application developed for residents, committee members, and society managers.

We respect your privacy and are committed to protecting user data. This Privacy Policy explains what information GrihaSabha processes, how it is used, and how your data is secured.

---

## 2. Information We Collect

### A. Account Information
To provide society management functionality, the app processes:
- **User Identifier:** Phone number, alphanumeric username, or a Google Account (via Google Sign-In / Firebase Authentication) for authentication.
- **Email Address:** Collected when you sign in with Google, or when provided directly, and used solely for account identification and login.
- **Member Name:** Display name within your society directory.
- **Flat/Unit Details:** Wing and flat number, and membership type (Owner, Tenant, or Household Help), used to route your society join request to the correct approvers.
- **Society Roles:** Assigned role (Resident Member, Committee Member, Society Manager, Guard) to enforce permission boundaries.
- **Society Join Requests:** When you request to join a society, your name, flat/wing, and membership type are shared with that society's Committee/Manager (or an existing approved member of the same flat) so they can approve or reject the request.
- **Push Notification Token:** A device-specific Firebase Cloud Messaging (FCM) token is used to deliver time-sensitive alerts (e.g., a visitor at the gate, meter reading reminders) to your device. This token does not identify you personally beyond routing notifications to your device/society topic.

### B. Society Operational Data
To enable society collaboration and accounting, the app manages:
- **Utility Meter Logs:** Electricity (`kWh`) and Water (`m³`) meter reading values, dates, timestamps, and notes.
- **Financial Ledgers:** Petty cash transactions (credit/debit entries) and society expense logs.
- **Community Notices & Polls:** Notices, resident acknowledgement logs, and voting entries on society polls.
- **Tasks & Complaints:** Delegated task status logs and maintenance complaint records.

---

## 3. How Information Is Used

Data processed by GrihaSabha is strictly used for the core functionality of housing society administration:
- Authenticating users into their designated housing society.
- Displaying utility consumption metrics and running financial balances.
- Transmitting society notices, poll results, and task updates.
- Maintaining transparency via society audit logs.

We **do not** sell, rent, monetize, or trade any personal or society data with third parties or advertising networks.

---

## 4. Third-Party Services & Data Transfers

- **Google Play Services:** Used for app distribution, updates, and standard Play Store diagnostics.
- **Google Sign-In / Firebase Authentication:** Used as an optional login method. Google shares your email address and basic profile info with the app upon your consent; this is verified against Google's own servers and never stored by any third party other than Google and our backend.
- **Firebase Cloud Messaging (FCM):** Used to deliver push notifications (visitor alerts, meter reminders, society notices) to your device via Google's infrastructure.
- **HTTPS Encryption:** All network traffic between GrihaSabha and the society backend server is encrypted using Transport Layer Security (TLS/HTTPS).
- **No Third-Party Advertising:** GrihaSabha does **not** include any third-party ads (AdMob, Facebook Ads, etc.) or user-tracking ad trackers.

---

## 5. Data Retention & Deletion

- **Local Data Storage:** App settings and local data are stored securely in Android's private app storage (Room Database / Encrypted DataStore).
- **Account & Data Deletion:** Users or Society Administrators can request account or society data removal by contacting society administration or emailing support at `chinmaysjoshi@gmail.com`.

---

## 6. Permissions Requested

GrihaSabha requests minimal required permissions:
- `INTERNET` / `ACCESS_NETWORK_STATE`: Required to sync society data with the backend server.
- `POST_NOTIFICATIONS`: (Android 13+) Required to deliver local notifications for society notices, reminders, task updates, and visitor gate alerts.
- `VIBRATE` / `WAKE_LOCK`: Used to get a resident's attention for a time-sensitive visitor alert at the gate.

---

## 7. Contact Us

If you have any questions or feedback regarding this Privacy Policy, please contact us:
- **Email:** `chinmaysjoshi@gmail.com`
- **Developer:** Chinmay Joshi
