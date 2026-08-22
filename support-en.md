# Support — JacArrow

**Last updated:** 2026-08-22
**Version covered:** v1.0+
**Contact:** galge.vender.0a@icloud.com

---

## Quick help

### How do I record an end?

1. Open JacArrow → tap **New session** on the Home tab
2. Choose location, target face, and round format → tap **Start session**
3. **Tap on the target face** to place each arrow — use pinch-zoom and the precision loupe for accuracy
4. Tap **Save end** when all arrows are placed
5. Repeat for each end until the round is complete

### What's the difference between X and 10?

The X-ring is the innermost ring and scores 10 points — same as the 10-ring. JacArrow tracks X separately because X is used as the tiebreaker in competitions. Tap the «X» button when an arrow hits the X-ring in score-pad mode.

### How do I correct a misplaced arrow?

1. Long-press the arrow on the target → the precision loupe activates
2. Drag the arrow to the new position → release
3. OR tap the arrow to select → tap **Delete** to remove it

In score-pad mode: tap the arrow badge in the score-pad and select a new value.

### What's post-recording (the 📋 icon)?

The 📋 icon marks sessions that were entered manually using the score pad, not recorded on the target with coordinates. Hit map, constellation, and spread analysis are not available for post-recorded sessions — only the score totals.

### How do I buy Pro?

1. Tap any Pro-locked feature (e.g. a theme locked with a Pro badge)
2. Paywall appears with **Buy Pro (NOK 299)** button
3. The store's purchase dialog appears → confirm (Face ID / passcode on iPhone, Google account on Android)
4. Pro activates immediately — all features unlock

**Price:** NOK 299 one-time purchase, lifetime. No subscription, no recurring charges.

### How do I restore purchases on a new phone?

1. Download JacArrow on the new phone (free version)
2. Sign in with the same account you bought Pro with — Apple ID on iPhone, Google account on Android
3. Open JacArrow → **Settings → License → Restore Purchases**
4. Pro reactivates automatically

A purchase cannot move between platforms: if you bought Pro on iPhone it does not apply on an Android phone, and the other way around. The stores do not allow it. If you've changed Apple ID or Google account: contact galge.vender.0a@icloud.com and we'll help you.

### How do I export my data?

**Settings → About the app → Export my data** → your phone's share sheet appears. Choose AirDrop, Mail, Files, Google Drive, or wherever you want to send the JSON file.

The JSON contains all sessions, rounds, arrows, goals, bow setups, and settings — complete portability under GDPR Art. 20.

### How do I delete all my data?

Uninstall JacArrow → both iOS and Android automatically remove the entire SQLite database and all settings. No residual data remains on the device.

If you've bought Pro: the receipt remains with the store you bought from — Apple or Google (for refund and support purposes). Uninstall doesn't affect future re-installs — Pro reactivates automatically via Restore Purchases.

### Which round formats are supported?

- **WA 720** (outdoor, 6 ends × 12 arrows = 72 arrows)
- **WA 18 m Indoor** (10 ends × 3 arrows)
- **WA 1440** (4 sequential distances)
- **Vegas Shoot** (10 ends × 3 arrows indoor 18 m)
- **AGB Portsmouth** (10 ends × 3 arrows indoor 20 yd)
- **NFAA Indoor** (12 ends × 5 arrows indoor 20 yd)
- **Free Training** (no format limits)

All formats include official WA Book 3 compliance: line-breaking rule, separate X tracking, correct ring radii.

### Which target faces are supported?

- **WA 122 cm 10-ring** (outdoor standard)
- **WA 80 cm 10-ring** (outdoor long distance)
- **WA 40 cm 10-ring** (indoor single-spot)
- **WA 40 cm Vegas 3-spot triangular** (indoor competition)
- **WA 40 cm Vegas 3-spot vertical** (indoor alternative)
- **AGB Portsmouth 60 cm 10-ring** (indoor UK)
- **NFAA indoor single-spot blue 40 cm** (USA)
- **NFAA indoor 5-spot blue 40 cm** (USA competition)

---

## Technical issues

### The app crashes on launch

1. Turn the phone off and on again
2. If still failing: uninstall and reinstall JacArrow (purchase data is NOT lost — the receipt remains with the store)
3. Send us a description at galge.vender.0a@icloud.com — what you were doing right before the crash, and which phone you have

**iPhone:** you can find the crash log yourself and include it: **Settings → Privacy & Security → Analytics & Improvements → Analytics Data** → find the JacArrow log → share with us. If you have «Share App Analytics» enabled, we receive crash logs automatically.

**Android:** crashes are reported to us automatically if you have «Usage & diagnostics» enabled in your phone settings. You don't need to do anything beyond describing what happened.

### Score data disappeared after update

JacArrow stores everything locally in SQLite. Updates migrate the database forward-only — old data is converted to the new format, never deleted.

If you experience data loss:
1. Verify you're signed in with the same account as before (Apple ID or Google account)
2. Check **Settings → About the app → Version number** — is it the latest?
3. Send us a description at galge.vender.0a@icloud.com

We have a strict rule that published migrations are immutable — data loss from updates should never happen. If it does, we have a bug and we want to hear about it.

### Pinch-zoom doesn't work on the target

1. Try with two fingers, not one
2. Check that you don't have reduced motion turned on — **iPhone: Settings → Accessibility → Motion**, **Android: Settings → Accessibility → Remove animations** — it can limit gestures in some apps
3. Force-close the app (swipe up from the bottom, swipe JacArrow up) and reopen

### The constellation vibrates when dragging

This was a bug in v0.28.2 and earlier — fixed in v0.28.3. Update the app to the latest version in the App Store or Google Play.

---

## Feedback and requests

### Suggest a new feature

Send an email to galge.vender.0a@icloud.com with:
- **What** you want (brief description)
- **Why** (what would it improve in your training?)
- **How often** would you use it (daily / per session / less frequently)

We read every single request and publish prioritized features in the app's «What's new» stream.

### Report a bug

Send an email to galge.vender.0a@icloud.com with:
- **What went wrong** (as detailed as you can)
- **What you expected to happen**
- **Step-by-step** to reproduce
- **Operating-system version and phone model** (iPhone: Settings → General → About · Android: Settings → About phone)
- **JacArrow version** (Settings → About the app)
- Screenshot if relevant

### General
We respond to all inquiries within 3 business days. Urgent issues (crashes preventing you from shooting) are prioritized higher.

---

## GDPR and privacy

For the full privacy policy: [Privacy](https://mjacobsen71.github.io/jacarrow-legal/privacy-en)

To export your data, delete a session, or exercise other GDPR rights: see the Privacy Policy.

Privacy complaints: contact us at galge.vender.0a@icloud.com **first**. If we can't resolve the matter, you can complain to your national data protection authority. For Norway: [Datatilsynet](https://www.datatilsynet.no/).

---

## About JacArrow

**Developer:** Morten Jacobsen, Norway
**Homepage:** [mjacobsen71.github.io/jacarrow-legal](https://mjacobsen71.github.io/jacarrow-legal)
**Privacy Policy:** [Privacy](https://mjacobsen71.github.io/jacarrow-legal/privacy-en)
**Licenses (open source):** See Settings → About the app → Licenses in the app

JacArrow is a solo-developer project built for archers at every level — from your first arrow to your hundredth tournament. WA Book 3 compliant scoring is there from day one, ready when you want it. Built with React Native + Expo + TypeScript + SQLite. No backend, no cloud, no tracking.

Thanks for using the app. 🏹
