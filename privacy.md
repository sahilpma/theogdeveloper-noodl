# Privacy Policy for Noodl

**Last updated:** April 13, 2026

**Developer:** The OG Developer  
**Contact:** sahilpm2602@gmail.com

---

## 1. Introduction

Welcome to Noodl ("the App," "we," "us," or "our"). Noodl is a task management and focus timer application designed to help you stay organized and focused. We are committed to protecting your privacy. This Privacy Policy explains what information we collect, how we use it, and your rights.

By using Noodl, you agree to the collection and use of information in accordance with this policy.

---

## 2. Information We Collect

### 2.1 Information Stored Locally on Your Device

All of your personal content is stored **exclusively on your device**. We do not have access to this data, and it is never transmitted to our servers or any third party. This includes:

- **Tasks** — Task titles, notes, due dates, completion status, and tags
- **Focus sessions** — Session duration, start/end times, and whether a session was ended early
- **Jotted thoughts** — Notes you write during focus sessions
- **Cumulative focus minutes** — Your total focus time tracker
- **App preferences** — Dark mode setting, notification preferences, haptics settings, and analytics consent choice

This data is stored in a local SQLite database and preferences file within the app's private storage on your device.

### 2.2 Information Collected Automatically

#### Crash Reports (Firebase Crashlytics)
When the app experiences a crash or error, we automatically collect:

- Crash reports and stack traces
- Device model and manufacturer
- Android OS version
- App version
- Non-fatal exception records

Crashlytics is **always active** in release versions of the app to help us identify and fix bugs. This service is provided by Google. Crash reports do not intentionally include your task titles, notes, or personal content.

#### App Event Logs
The app maintains a local log file of app events (e.g., startup, navigation, feature usage, errors). These logs:

- Are stored only on your device in the app's cache directory
- Are retained for **7 days** and then automatically overwritten
- Contain **no task content, notes, or personal data**
- Are only shared externally if you **voluntarily** submit a bug report and explicitly consent to include logs

### 2.3 Information You Voluntarily Provide

#### Feedback and Bug Reports
If you choose to send feedback or report a bug, you may provide:

- Your message (required)
- Your email address (optional)
- 7 days of app event logs (only if you explicitly consent)
- Your Firebase Installation ID (only if you have analytics opt-in enabled)
- Device model, Android version, app version, and a hashed device identifier (collected automatically)

This information is sent to our backend server hosted on Amazon Web Services (AWS) in the **Mumbai, India (ap-south-1)** region. Logs uploaded as part of bug reports are stored for **30 days** and then automatically deleted.

### 2.4 Analytics (Opt-In Only)

Firebase Analytics is **disabled by default**. We only collect anonymous usage data if you explicitly opt in during setup or in Settings > Data & Privacy.

If you opt in, we collect:

- Event names (e.g., `task_created`, `focus_session_started`, `onboarding_completed`)
- Minimal numeric parameters (e.g., focus session duration in minutes)

We **never** collect:

- Task titles or content
- Notes or jotted thoughts
- Email addresses or names
- Any personally identifiable information
- Device identifiers or advertising IDs

You can revoke your analytics consent at any time in **Settings > Data & Privacy > Anonymous Usage Data**.

---

## 3. Android Permissions

Noodl requests the following Android permissions:

| Permission | Purpose |
|---|---|
| `POST_NOTIFICATIONS` | To send daily task reminder notifications (local notifications, not push) |
| `REQUEST_IGNORE_BATTERY_OPTIMIZATIONS` | To prevent Android from killing the focus timer when the app is in the background |
| `VIBRATE` | To provide haptic feedback on task completion and interactions |
| `RECEIVE_BOOT_COMPLETED` | To reschedule scheduled tasks (like daily reminders) after your device reboots |
| `INTERNET` | Required only for Firebase Crashlytics and if you voluntarily submit feedback |
| `FOREGROUND_SERVICE` / `FOREGROUND_SERVICE_SPECIAL_USE` | To keep the focus timer running as a foreground service with notification controls |

Noodl does **not** request access to your camera, location, contacts, microphone, storage, or calendar.

---

## 4. How We Use Your Information

We use the collected information solely for the following purposes:

- **To provide and maintain the app** — Storing your tasks, focus sessions, and preferences locally
- **To improve the app** — Understanding how features are used (only if you opt in to analytics) and fixing crashes
- **To respond to your feedback** — Addressing bugs and suggestions you submit
- **To send local notifications** — Daily task reminders, if you enable them

We do **not** use your information for advertising, profiling, or any purpose beyond improving and operating Noodl.

---

## 5. Third-Party Services

Noodl integrates with the following third-party services, each of which has its own privacy policy:

### 5.1 Firebase (Google)
- **Firebase Crashlytics** — Crash reporting and stability monitoring
  - Privacy Policy: https://firebase.google.com/support/privacy
  - Always active in release builds
- **Firebase Analytics** — Anonymous usage statistics
  - Privacy Policy: https://firebase.google.com/support/privacy
  - **Opt-in only** — disabled by default
- **Firebase Installations** — Identifies your app instance (only used when you submit a bug report with analytics linked)

### 5.2 Amazon Web Services (AWS)
- **API Gateway, Lambda, S3, DynamoDB, SES** — Backend infrastructure for feedback and bug report submissions
  - Privacy Policy: https://aws.amazon.com/privacy/
  - Used **only** when you voluntarily submit feedback
  - Located in the **ap-south-1 (Mumbai, India)** region
  - Uploaded logs are deleted after 30 days

### 5.3 Open Source Libraries
Noodl uses various open-source libraries (e.g., OkHttp, Timber, Kotlin Coroutines). These libraries operate entirely within the app on your device and do not transmit data externally.

---

## 6. Data Sharing and Disclosure

We do **not** sell, rent, or share your personal information with any third party for advertising or marketing purposes.

We may disclose information only in the following circumstances:

- **With your consent** — When you voluntarily submit a bug report and consent to share logs
- **For legal obligations** — If required by law, regulation, or legal process
- **To protect rights** — To protect the safety, rights, or property of The OG Developer, users, or the public

---

## 7. Data Retention

- **Local data** — Retained on your device until you delete it or uninstall the app
- **App event logs** — Retained locally for 7 days
- **Feedback logs (AWS S3)** — Retained for 30 days, then automatically deleted
- **Crash reports (Firebase Crashlytics)** — Retained per Google's data retention policies

---

## 8. Your Rights and Choices

### 8.1 Access and Export
You can export all of your task data at any time as a CSV file via **Settings > Data & Privacy > Export Tasks (CSV)**.

### 8.2 Deletion
You can delete all of your data at any time via **Settings > Data & Privacy > Delete All Data**. You can also delete all data by uninstalling the app from your device.

### 8.3 Analytics Consent
You can opt in or out of anonymous usage analytics at any time via **Settings > Data & Privacy > Anonymous Usage Data**.

### 8.4 App Permissions
You can manage app permissions at any time through your device's system settings.

---

## 9. Children's Privacy

Noodl is not directed to children under the age of 13 (or the applicable minimum age in your jurisdiction). We do not knowingly collect personal information from children. If you believe a child has provided us with personal information, please contact us at sahilpm2602@gmail.com.

---

## 10. Data Security

We take reasonable measures to protect your information:

- All personal content is stored in the app's private, sandboxed storage on your device, which is protected by Android's security model
- Data transmitted to our feedback backend (AWS) uses HTTPS/TLS encryption
- AWS services have server-side encryption (AES-256) enabled for stored data
- Firebase services use Google's infrastructure encryption

However, no method of electronic transmission or storage is 100% secure, and we cannot guarantee absolute security.

---

## 11. Changes to This Privacy Policy

We may update this Privacy Policy from time to time. We will notify you of any changes by posting the new Privacy Policy on this page and updating the "Last updated" date. Significant changes may be communicated through in-app notices.

---

## 12. Contact Us

If you have any questions about this Privacy Policy or our data practices, please contact us:

- **Email:** sahilpm2602@gmail.com
- **Developer:** The OG Developer

---

*This Privacy Policy applies to the Noodl application for Android, package name `com.theogdeveloper.noodl`.*
