# Privacy Policy for Noodl

**Last updated:** September 26, 2026 (applies to Noodl 2.1.0 and later)

**Developer:** The OG Developer  
**Contact:** sahilpm2602@gmail.com

The current version of this policy always lives at
**https://sahilpma.github.io/theogdeveloper-noodl/privacy**. That is the only official
address; the app, the Play listing and our terms all link here.

---

## 1. Who we are

Noodl is a to-do list and focus timer for Android, made by The OG Developer, an independent
developer based in India ("we", "us"). We decide what data Noodl handles and why, so for data
protection law we are the party responsible for it (the "controller" under the EU and UK GDPR,
the "Data Fiduciary" under India's Digital Personal Data Protection Act, 2023).

For any privacy question, request or complaint, write to **sahilpm2602@gmail.com**. The same
address is our grievance contact for India. We answer within one month.

---

## 2. The short version

- **Your tasks never leave your phone through us.** Tasks, notes, jotted thoughts and focus
  history are stored on your phone. We never receive them, and there is no account.
- **Crash reports are always on.** When something breaks, a technical report goes to Google
  Firebase so we can fix it. It never contains your tasks.
- **Usage analytics are off unless you turn them on.** Nothing is collected until you switch
  them on, and the advertising ID is never collected.
- **Feedback and bug reports leave only when you send one.** App logs go with a bug report only
  if you tick the box, which starts unticked.
- **Android backup is on, and end-to-end encrypted.** Your tasks and settings can come with you
  to a new phone, through your own Google account. We can't read that backup.
- We don't sell data, show ads, or build profiles. We don't ask about or record any diagnosis
  or health information.

---

## 3. What stays on your phone

Noodl stores the following in its private storage on your phone:

- **Tasks:** titles, notes, dates, whether they're done, and their order
- **Focus sessions:** length, start and end times, and whether a session ended early
- **Jotted thoughts:** what you type during a focus session
- **Your focus total:** the running count of minutes you've focused
- **Settings:** theme, reminder time, timer length, your analytics choice and similar choices
- **The app log:** a record of app events such as "app started", "session ended" or an error
  code. It holds only IDs, counts and times, never task titles, notes or thoughts. Noodl keeps
  7 days of it and deletes older entries. It stays on your phone unless you attach it to a bug
  report.
- **Exports:** when you export, Noodl writes a CSV file of your tasks, thoughts and focus
  sessions into its private temporary folder and hands it to the app you pick in Android's
  share sheet. Where it goes from there is your choice. Noodl deletes earlier export files.

The home-screen widget and the Quick Settings tiles show what's on your list on your own
screen. Anyone holding your unlocked phone can see them, the same as the app itself.

---

## 4. Android backup and moving to a new phone

Noodl lets Android back up its task database and settings, and copy them to a new phone:

- **Cloud backup** goes to your own Google account, and only if it can be end-to-end
  encrypted with your phone's screen lock (PIN, pattern or password). If your phone can't do
  that, Noodl is left out of the cloud backup. We never see or receive this backup.
- **Device-to-device transfer** copies the same data straight from your old phone to the new
  one when you set it up.
- **Left out of both:** the app log, exported files, temporary files, and settings that only
  make sense on one phone (such as which Quick Settings tiles are added).

You control backup in your phone's settings (usually Settings › Google › Backup). Google
handles the backup under its own privacy policy: https://policies.google.com/privacy

---

## 5. Crash reports (always on)

Noodl uses three Google Firebase services that are on for everyone, because a crash we can't
see is a crash we can't fix. There is no switch for them in the app.

- **Firebase Crashlytics** sends a report when the app crashes or catches a serious error. It
  contains the technical trace of what failed, your phone's model and manufacturer, Android
  version, Noodl version, basic device state (such as free memory and disk space), the time,
  and short notes the app adds about the error (an error code, never your content).
- **Firebase Sessions** sends a small signal when the app is opened (a session number and
  times), so crash rates can be measured against how often the app is used.
- **Firebase Installations** gives this copy of Noodl a random installation ID that ties the
  above together. It is not your name, email, phone number or advertising ID. It stays the
  same until you uninstall Noodl or clear its storage; "Delete all data" doesn't change it.

Crash reports never include task titles, notes or thoughts. Google keeps crash reports for 90
days. Details: https://firebase.google.com/support/privacy

---

## 6. Usage analytics (off unless you turn them on)

Firebase Analytics is **off from the moment Noodl is installed**. Nothing is collected until
you switch it on during setup or in **Settings › Data & Privacy › Analytics**.

If you switch it on, Google Analytics for Firebase receives:

- which of these happened: a task was created or completed, a focus session started (with the
  minutes you chose) or finished (with how long it ran and whether it ended early), a thought
  was jotted or turned into a task, setup was finished or skipped, and a review request was
  shown
- Firebase's standard app events, such as the first open, app updates and time spent in the app
- a random app-instance ID for this copy of Noodl, your phone model, Android version, app
  version and language, and your approximate location (country and city level), which Google
  works out from your internet address

It never receives task titles, notes, thoughts, your name or your email. **Noodl never
collects the advertising ID:** the app doesn't hold the permission to read it, advertising-ID
collection is switched off, and no data is used for ad personalisation.

Switching analytics off stops collection at once and clears the analytics data stored on your
phone, including the app-instance ID. Event data already sent stays with Google for up to 14
months; after that only totals remain, which don't identify anyone. Because it isn't linked to
your name or email, we usually can't find your data to delete it earlier.

---

## 7. Feedback and bug reports (only when you send one)

**Settings › Help & Support** lets you send feedback or report a bug. Nothing is sent until you
tap Send. A report contains:

- your message
- your email address, only if you type one (so we can reply)
- your phone's model, Android version and Noodl version
- a short device code made from your phone's Android ID for Noodl. It is the same every time
  you send from this phone, so we can tell reports from one phone apart. It can't be turned
  back into the Android ID and doesn't say who you are.
- **only if you tick "Include 7 days of app logs"** (off until you tick it): the last 7 days of the app
  log described in section 3. It is uploaded separately. If that upload fails, the app puts the
  log text into the report itself, and it is then kept as long as the report.
- **only if analytics is on and you switch on "Link to crash reports"** (off until you do): the Firebase
  installation ID from section 5, so your report can be matched with crash reports

Where it goes: our own server on **Amazon Web Services in Mumbai, India** (region ap-south-1).
Once a day, new reports are emailed to our inbox (Gmail) so we can read them.

How long we keep it:

- **Reports:** 12 months, then deleted automatically. Our database's recovery backups can hold
  a copy for up to 35 more days.
- **Uploaded logs:** 30 days, then deleted automatically. The deletion can take a few extra
  days to finish.
- **The daily email copy:** only as long as we need it to deal with your report, and no longer
  than 12 months.

You can ask us to delete a report sooner. Write from the email address you gave, or tell us
roughly when you sent it and what it said.

---

## 8. Other Google services

- **Google Play in-app review:** now and then, at a good moment such as a finished focus
  session, Noodl may ask Google Play to show its rating card. Google Play handles the card and your rating under your Google
  account. We don't see who you are unless you post a public review.
- **Google Play** itself (installs and updates) works under Google's terms, not ours.

---

## 9. Android permissions

| Permission | Why Noodl has it |
|---|---|
| `POST_NOTIFICATIONS` | To show the daily reminder, the running focus timer with its Pause and End buttons, and the "session done" notice. On Android 13 and later, Android asks you the first time you start a focus session or turn on the reminder. |
| `SCHEDULE_EXACT_ALARM` | So the focus timer ends and the daily reminder arrives on time. On Android 14 and later you grant it yourself: Noodl's optional **On-time timer and reminders** row in Settings opens the right page. Without it Noodl still works, and alarms can arrive a little later. |
| `RECEIVE_BOOT_COMPLETED` | To set the daily reminder, the overnight move of unfinished tasks to Plan, and the widget's midnight refresh again after your phone restarts. |
| `FOREGROUND_SERVICE`, `FOREGROUND_SERVICE_SPECIAL_USE` | To keep the focus timer running, with its notification, while you use other apps. |
| `VIBRATE` | For gentle haptic feedback, and the buzz when a session ends. |
| `INTERNET` | For crash reports, analytics if you turn them on, sending feedback, and Google Play's rating card. |

Added automatically by Google's and Android's own libraries:

| Permission | What it's for |
|---|---|
| `ACCESS_NETWORK_STATE` | Lets background work wait for a connection before sending. |
| `WAKE_LOCK` | Lets Android's background-work and Firebase libraries finish sending a report. |
| `BIND_GET_INSTALL_REFERRER_SERVICE` | Lets Google Analytics, only when you've switched it on, see which store link led to the install (for example a link on our blog). |
| `DYNAMIC_RECEIVER_NOT_EXPORTED_PERMISSION` | An internal Android permission that keeps Noodl's own messages inside Noodl. |

Noodl **no longer asks** to be exempted from battery optimisation; Settings can open Android's
own battery page if you want to change it there. It **does not have** the advertising-ID
permissions, and it never asks for your camera, microphone, location, contacts, calendar,
photos, files or phone.

---

## 10. Why we use your data, and on what legal basis

| What | Why | Legal basis (EU and UK GDPR) |
|---|---|---|
| Your tasks and everything else in section 3 | To run the app | Stays on your phone; we never receive it |
| Crash reports and sessions (section 5) | To find and fix crashes and keep the app stable | Our legitimate interest in a working app. You can object by writing to us |
| Usage analytics (section 6) | To see which parts of the app get used | Your consent, given with the switch. You can withdraw it at any time with the same switch |
| Feedback and bug reports (section 7) | To read, answer and fix what you report | Your consent, given by choosing to send the report and, for logs, by ticking the box |
| Any of the above, when the law requires it | To meet a legal obligation | Legal obligation |

Withdrawing consent doesn't affect what was processed before you withdrew it.

---

## 11. Who else handles the data, and where

We don't sell, rent or share personal data for advertising or marketing. These companies handle
data for us, under their own security and privacy terms:

- **Google** (Firebase Crashlytics, Sessions, Installations and Analytics; Gmail for the daily
  report email; Google Play). Data may be processed in the **United States** and other
  countries. Google is certified under the EU-U.S. Data Privacy Framework, and its terms
  include the EU Standard Contractual Clauses.
- **Amazon Web Services** (our feedback server: API Gateway, Lambda, S3, DynamoDB, and SES for
  the daily email). Data is stored in **Mumbai, India**. AWS's data processing terms include
  the EU Standard Contractual Clauses.
- **Us.** We work from India, so reports you send are read and handled there.

We may also disclose information if the law requires it, or to protect the safety of users or
the public.

---

## 12. How long it's kept

| Data | Kept for |
|---|---|
| Tasks, thoughts, sessions, focus total, settings (on your phone) | Until you delete them, use "Delete all data", clear Noodl's storage, or uninstall |
| The app log (on your phone) | 7 days |
| Crash reports (Google) | 90 days |
| The installation ID | Until you uninstall Noodl or clear its storage |
| Analytics data, if you turned analytics on (Google) | Up to 14 months |
| Feedback and bug reports (AWS, Mumbai) | 12 months, plus up to 35 days in recovery backups |
| Logs uploaded with a bug report (AWS, Mumbai) | 30 days |
| The daily report email (Gmail) | As long as needed to deal with the report, at most 12 months |
| Android backup (your Google account) | Under your backup settings and Google's policy |

---

## 13. Your choices and rights

- **Export:** Settings › Data & Privacy › Export gives you a CSV of your tasks, thoughts and
  focus sessions.
- **Delete everything on your phone:** Settings › Data & Privacy › **Delete all data** removes
  your tasks, thoughts, focus history and total, settings, export files and the app log. It
  also cancels the daily reminder, stops a running focus timer, and resets the analytics ID.
  The only thing it keeps is a note of which Quick Settings tiles are on your phone, so those
  tiles keep working. Uninstalling Noodl removes everything.
  - It can't reach copies that already left the phone: your Android backup (the next backup
    replaces it, or delete it in your Google account's backup settings), crash reports and
    analytics at Google (they expire as in section 12), and reports you sent us (ask us).
- **Analytics:** switch it on or off at any time in Settings › Data & Privacy › Analytics.
- **Permissions:** change them at any time in your phone's settings.

Depending on where you live, you have the right to ask us for a copy of your personal data, to
correct it, to delete it, to limit or object to how we use it, to receive it in a portable
format, and to withdraw consent. In India you can also name someone to exercise your rights if
you die or can't act for yourself. Write to **sahilpm2602@gmail.com**. We may ask you to
confirm the report is yours (for example, by writing from the address you gave), and we answer
within one month.

Most of what we hold can't be linked to you by name. We can find a bug report from the email
address in it or from a description of when you sent it and what it said.

**If you're unhappy with our answer, you can complain to a regulator:**

- in the EU or EEA, your country's data protection authority (list:
  https://edpb.europa.eu/about-edpb/about-edpb/members_en)
- in the UK, the Information Commissioner's Office: https://ico.org.uk/make-a-complaint/
- in India, the Data Protection Board of India. Indian law asks you to raise it with us first,
  at the grievance contact in section 1, before going to the Board.

---

## 14. Children

Noodl is not directed at children under 13, and we don't knowingly collect personal data from
them. In India, data protection law treats everyone under 18 as a child and requires a parent's
or guardian's consent; we don't knowingly collect data from anyone under 18 in India without it.
Noodl never asks your age. If you believe a child has sent us information, write to us and we'll
delete it.

---

## 15. Security

- On your phone, Noodl's data sits in its private storage, protected by Android's app sandbox
  and your phone's own encryption.
- Everything Noodl sends travels over encrypted connections (HTTPS).
- Our feedback server encrypts stored reports and logs (AES-256), Google encrypts Firebase data,
  and Android's cloud backup of Noodl is end-to-end encrypted with your screen lock.

No method of storage or transmission is completely secure. If a breach ever affected your data,
we would tell the people affected where we can reach them, and the authorities, as the law
requires.

---

## 16. Changes to this policy

When this policy changes, we update the date at the top and publish the new version at the
address above. Significant changes are also mentioned in the app's release notes on Google
Play.

**What changed on September 26, 2026:** app logs are now kept on your phone for 7 days and the
"Include 7 days of app logs" box starts unticked; analytics is off from the very first launch and never
collects the advertising ID (the advertising-ID permissions were removed); feedback records
are now deleted after 12 months, and older versions of uploaded logs are really deleted after 30
days; "Delete all data" now removes everything listed above; Android backup and device transfer
are now on, end-to-end encrypted; the battery-exemption permission was removed and the
on-time-alarm permission added; and this policy now states legal bases, transfers, retention
and how to complain.

---

## 17. Contact us

- **Email:** sahilpm2602@gmail.com
- **Developer:** The OG Developer

---

*This Privacy Policy applies to the Noodl application for Android, package name
`com.theogdeveloper.noodl`. Our blog at noodl.prepshotz.com has its own short privacy page.*
