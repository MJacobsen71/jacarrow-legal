# Privacy Policy — JacArrow

**Last updated:** 2026-08-22
**Data Controller:** Morten Jacobsen, Norway
**Contact:** galge.vender.0a@icloud.com

---

## Short version

JacArrow stores **all your data locally on your device**. We have no
servers that receive your shoots, sessions, or goals. When you uninstall
the app, all data is gone.

The only third parties that receive information are:
- **Apple** (if you use the app on iPhone) — handles App Store purchases
- **Google** (if you use the app on Android) — handles Google Play purchases
- **RevenueCat** (after you purchase Pro) — verifies your purchase
- **Sentry** (only if you opt in to crash reporting) — receives anonymous crash data to help us fix bugs

Which of Apple and Google is involved depends on the store you downloaded
the app from. Neither is involved in your shooting data itself.

You have full GDPR rights to access, deletion, and data portability.

---

## What we store

### On your device (locally, never leaves the phone)
- **Shooting data:** sessions, rounds, arrow placements, scores, tags, goals, bows, and arrow sets
- **Settings:** selected language, theme, dominant hand, competition class, notification toggles
- **App history:** coach-mark status (which tips you have seen), tutorial-completed flags

All this data is stored in an SQLite database and AsyncStorage on your phone.
Neither JacArrow nor any third party has access to this data. There is no user
account, no cloud storage, and no syncing between devices — your data stays on
the device you recorded it on.

### Notifications (scheduled locally on the device)
JacArrow can send you notifications: that you have set a personal record,
that your trial period is nearing its end, or reminders about your goals.

All of these are **scheduled locally on your device** and computed from data
that never leaves it. We have no server sending notifications, and we never
receive a notification token, a delivery receipt, or any record of what you
did with a notification. Delivery itself is handled by the operating system on
your phone (iOS or Android), the same way as an alarm you set yourself.

You can turn notifications off at any time — both inside JacArrow under
**Settings → Notifications**, and in your phone's own settings.

---

## Third parties

### Apple App Store (on iPhone)
If you downloaded JacArrow from the App Store, all in-app purchases are
handled by Apple. We never receive card information, addresses, or other
payment details. Apple's
[Privacy Policy](https://www.apple.com/legal/privacy/) applies to the
purchase flow.

### Google Play (on Android)
If you downloaded JacArrow from Google Play, all in-app purchases are handled
by Google via Google Play Billing. We never receive card information,
addresses, or other payment details — we are only told that a purchase
completed and is valid. Google's
[Privacy Policy](https://policies.google.com/privacy) applies to the purchase
flow.

Note that Google Play, unlike the App Store, does **not** share an in-app
purchase with a family group. That is a difference between the stores, not
something we control.

### RevenueCat (only after Pro purchase)
When you purchase JacArrow Pro, RevenueCat records your receipt and an
anonymous `appUserId` (a UUID generated on your device). This is necessary
for the app to verify your purchase on later use and during «Restore
Purchases». The receipt comes from the App Store or Google Play, depending on
where you bought it. RevenueCat's
[Privacy Policy](https://www.revenuecat.com/privacy) applies. We never send
your name, email, or other personal data.

### Operating-system analytics and crash data
Both Apple and Google can send developers anonymous, aggregated counts about
usage and crashes — but only if **you** have turned that on in your phone's
own settings. This is a store feature, not ours: we see totals only, never
anything traceable to you. We use it for bug fixes and performance
optimization.

- **iPhone:** controlled by «Share App Analytics». Turn it off via
  **Settings → Privacy & Security → Analytics & Improvements**.
- **Android:** controlled by «Usage & diagnostics». Turn it off via
  **Settings → Google → Usage & diagnostics** (the exact name varies slightly
  between manufacturers).

### Sentry (only if you have enabled crash reporting)
Sentry is an error monitoring service that helps us identify and fix bugs
in JacArrow. Sentry only receives data if you have **explicitly opted in**
via **Settings → Privacy → Crash reports** (the toggle is OFF by default).

When opted in, the following is sent to Sentry's EU servers (Germany):
- Crash stack traces (file names, line numbers, exception types)
- Device model and operating-system version (iOS or Android)
- App version and build number

We do **not** send:
- Personal information (no name, no email, no user ID linked to identity)
- Performance traces or transactions (`tracesSampleRate: 0`)
- IP addresses (`sendDefaultPii: false`)

You can disable crash reporting at any time via the same toggle. When
disabled, Sentry is **not initialized** and no network requests are made.
Sentry's [Privacy Policy](https://sentry.io/privacy/) applies to data
received.

---

## What we do NOT collect

- No user account, email address, or password
- No cloud storage, no backup to our servers, no syncing between devices
- No GPS or location data
- No access to contacts, calendar, camera, or microphone
- No third-party trackers (Firebase Analytics, Google Analytics, Facebook Pixel, etc.)
- No advertising identifiers (IDFA on iOS, Advertising ID on Android)
- No video tracking or device fingerprinting

---

## Your rights (GDPR)

You have the following rights under the General Data Protection Regulation:

**Right of access (Art. 15):** All your data is stored locally on your device.
You have full visibility via:
- Settings → My sessions (all historical rounds)
- Settings → My goals (all active and archived goals)
- Settings → Bows / Arrow sets / Locations (equipment management)

**Right to data portability (Art. 20):** Use
**Settings → Export my data** to download all your data as a JSON file. The
file can be shared via your phone's share sheet to email, AirDrop, Files,
Google Drive, etc. This is your complete shooting history in a standard
format.

**Right to erasure (Art. 17):**
- *Delete individual session:* swipe the session on the home screen → Delete
- *Delete all data:* uninstall JacArrow — both iOS and Android automatically
  delete the entire SQLite database and AsyncStorage. The receipt for a Pro
  purchase is retained by the store you bought from (Apple or Google) and by
  RevenueCat for refund and support purposes.

**Right to restriction and objection (Art. 18–21):** JacArrow does not
make any automated decisions about you. The Smart Insights engine only
analyzes your own training data locally on your device and presents
observations — it makes no decisions on your behalf.

**Right to withdraw consent (Art. 7):** Analytics consent for Apple and
Google is controlled in your phone's own settings (see «Operating-system
analytics and crash data» above). Crash reporting to Sentry is turned off
inside JacArrow under **Settings → Privacy**. RevenueCat data is deleted when
you delete the Apple ID or Google account the purchase was made with.

---

## Changes

We will update this policy when significant changes occur in how we process
data. Changes are communicated via:
1. «Last updated» date at the top of this page
2. In-app banner on first launch after update if the change is substantial
   (e.g. new third parties, new data collection)

---

## Complaints

If you believe we are processing your personal data in violation of GDPR,
you have the right to complain to your national data protection authority:

- **Norway:** [Datatilsynet](https://www.datatilsynet.no/)
- **EU/EEA:** find your authority at
  [edpb.europa.eu](https://www.edpb.europa.eu/about-edpb/about-edpb/members_en)

We encourage you to contact us first at galge.vender.0a@icloud.com — we take
all privacy inquiries seriously.
