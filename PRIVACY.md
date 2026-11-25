# GymChal Privacy Policy

**Effective date:** 25 November 2026

**App:** GymChal (iOS and Android)  
**Bundle ID:** `com.gymchal.app`  
**Operator / Data Fiduciary:** Jalal Najafi

GymChal is a fitness accountability app for adults in India. It helps you and an optional gym buddy stay consistent by checking in at your gym, tracking weekly targets and streaks, and sending nudges and reactions. This policy describes the personal data the app is built to collect and process. It does not invent features the product does not have.

If you have questions, or want to exercise your rights, contact **[najafi.jalal.cse@gmail.com](mailto:najafi.jalal.cse@gmail.com)**.

## The short version

- We collect only what is needed to run your account, verify gym check-ins, pair you with a buddy, and send the notifications you allow.
- We do not show ads, we do not sell your data, and we do not buy or sell personal information.
- We do not collect health, fitness-band, or medical data.
- Your live location is used only when you tap Check in. We do not track you in the background or store a route.
- You can download a copy of key account data, withdraw optional consents, and delete your account in the app. Deletion erases your account and related server data.

## Who we are

Jalal Najafi operates GymChal and is the Data Fiduciary under India’s Digital Personal Data Protection Act, 2023 (DPDP Act).

Account and app data are processed with Google Firebase in the `asia-south1` region (Mumbai, India), in Firebase project `gymchal-app-in`. Apple also processes data when you download the app, use TestFlight, or receive push notifications through Apple Push Notification service.

## Information we collect

### Account and profile

- **Account ID.** When you start the app we create an anonymous Firebase Authentication identifier, which becomes your account ID.
- **Phone number.** You can sign in with an Indian mobile number (`+91`, 10 digits). We send a one-time SMS code through Firebase Phone Authentication and link that number to your anonymous account so your data stays with the same ID. If the number already belongs to another GymChal account, you are signed in to that existing account; the anonymous session is not merged.
- **Date of birth.** Collected so we can confirm you are 18 or older. If you are under 18, we do not create an account and we do not save what you entered.
- **Display name** and an optional **preset avatar** (a built-in icon key, not a photo of you).
- **Weekly target** (how many gym days you aim for each week) and related streak and grace-token values that the service calculates.
- **Settings** you choose in the app, such as notification preferences, language (English or Hinglish), theme, and whether to hide your gym name from your buddy.
- **Consent records.** We store which purposes you granted or withdrew, and a timestamped consent log.

The app also includes email and Google sign-in screens. Those flows currently only start an anonymous session. They do not complete real email or Google authentication, and we do not collect a Google account or use your email as a live sign-in identifier.

### Your gym

You choose a home gym. We store its name, area, city, coordinates, check-in zone, and whether you have chosen to hide the gym name from your buddy.

### Location at check-in

GymChal uses your location **only when you tap Check in**, and only with When-In-Use permission. The app does not use background location and does not record a live route.

When you check in, the app sends your current GPS coordinates, reported accuracy, and whether the reading appears to be a mock location to our server. The server compares that position with your saved gym (within 150 metres, with sufficient accuracy) and requires you to stay long enough (at least 30 minutes) before the check-in is counted. We store the gym coordinates, the calculated distance, timestamps, and the result of the check-in (for example arrived, confirmed, or rejected, and the reason). We do not store a trail of GPS points or your route. Mock or spoofed locations are rejected.

A check-in can be counted once per India (IST) day.

### Check-in history, streaks, and weeks

We store your check-in history, whether a day counted, weekly counts against your target, streak and grace status, and week results (including, for paired users, shared streak information). Weeks are calculated in Indian Standard Time (IST).

### Pairing, invites, nudges, and reactions

If you pair with a buddy we store the pair membership, each person’s weekly target, shared streak information, and when the pair started or ended.

You can create a one-time invite code (valid for 7 days). We store the code, who created it, expiry, and, if it is used, who accepted it. You may share a code yourself, for example through WhatsApp or in person. The app does not read your device contacts.

You can send your buddy a nudge (from a short, predefined set of messages, limited to three per sender per IST day) and a reaction on a confirmed check-in (from a fixed set of emoji). We store those events as needed to deliver them and to enforce the limits.

### Notifications

If you allow notifications, we store a Firebase Cloud Messaging (FCM) push token for your device, together with your account ID, platform, and an update time, so we can send nudges, reminders, and pair-related notices. We also keep an in-app notification feed.

The app may also schedule a **local** reminder on your device for the 30-minute check-in stay. That local reminder is stored on the device, not on our server.

You can turn optional notification consent off in Me → Privacy → Consent & data rights.

### Information stored on your device

The app keeps some data locally so it can work (for example a signed-in session, cached profile and consent state, and display settings). Clearing or deleting the app removes this local copy. It does not by itself delete your server account; use Delete account in the app for that.

### Optional analytics and crash reports

Anonymous usage analytics and crash reports (Firebase Analytics and Firebase Crashlytics) are **off unless you opt in**. You can grant or withdraw this consent at any time in the app. Withdrawal stops further collection.

### Information we do not collect

- Health, heart-rate, workout, or medical data
- Your device contacts (the contacts picker is not connected to the address book)
- Photos, camera roll, or a profile photograph
- Precise live location or movement outside the check-in you start
- Payment card details (GymChal does not process payments in the current product)
- Advertising identifiers for ads (we do not show ads)

## What your gym buddy can and cannot see

If you are paired, your buddy can see that you checked in and completed a session, your gym name unless you hide it, and a time-of-day period (morning, afternoon, or evening) in history.

Your buddy does **not** see your live location or route, any health data, or exact check-in times in history. They also do not see your phone number, date of birth, or consent log through the product.

## How we use information

We use this information to:

- create and secure your account, including phone one-time-code sign-in
- confirm you are 18 or older
- verify gym check-ins and keep your history, streaks, and weekly targets
- run pairing, invites, nudges, and reactions
- send the notifications you have allowed
- honour your privacy choices (for example hiding your gym name)
- improve the app if you opt in to anonymous analytics and crash reports
- respond to your requests, including export or deletion
- maintain security and prevent abuse (for example rejecting mock locations or enforcing daily limits)

## Legal basis (DPDP Act)

We process your personal data for the purposes you consent to in the app:

- **Required to use GymChal:** account and pairing (including your name and phone number), and gym check-in location only when you tap Check in. If you withdraw a required consent, we cannot keep the account running and we will offer to erase your data.
- **Optional:** nudges and reminders, and anonymous analytics and crash reports. You may withdraw these at any time without deleting your account.

You may also have rights under other laws that apply to you.

## How we share information

We do not sell your personal data. We do not share it for advertising.

We share data only:

- **With your buddy,** as described above, if you choose to pair.
- **With service providers who process data on our behalf:**
  - **Google Firebase** (Google LLC / Google India as applicable): Authentication, Cloud Firestore, Cloud Functions, Cloud Messaging, and, if you opt in, Analytics and Crashlytics. Functions and Firestore for this app are configured in `asia-south1`.
  - **Apple:** App Store and TestFlight distribution, in-app purchase infrastructure if used in future, and Apple Push Notification service when a notice is delivered to an iOS device.
- **When you choose to share something yourself,** such as an invite code or a share card, with an app like WhatsApp. That destination’s own privacy policy then applies to what you send.
- **If required by law,** or to protect the rights, safety, or security of users or the service.

## Data retention

We keep your account data for as long as your account is active. We do not currently run a separate automatic deletion schedule for active accounts.

Invite codes expire after 7 days. Push tokens that Firebase reports as invalid are removed. Notification and activity records are kept while the account exists, unless you delete the account.

If you delete the app without deleting the account, server-side data remains until you delete the account or ask us to erase it.

## Deletion, export, and your rights

In the app (Me → Privacy, and Consent & data rights) you can:

- **Review and change consents,** including withdrawing optional analytics or notifications.
- **Download my data,** which exports a copy of your profile name, weekly target, gym, streak and grace figures, consents, and consent log. If you need a broader copy, email us.
- **Delete your account / Erase my data.** You must type `DELETE` to confirm. In Firebase mode this calls our `deleteAccount` function, which:
  - leaves any active pair (your partner keeps their own history; shared pair-week records remain)
  - deletes your check-ins, push tokens, invites you created, notification feed items, nudges, reactions you sent or received, day markers, solo week records, your user profile (including date of birth, consents, and settings), and your Authentication account
  - cannot be undone

You may also email **[najafi.jalal.cse@gmail.com](mailto:najafi.jalal.cse@gmail.com)** to access, correct, or erase your data, withdraw consent, or raise a grievance. We will need enough information to verify that the request is yours.

Under the DPDP Act you may also have the right to withdraw consent, to request access or erasure, and to complain to the Data Protection Board of India.

## Children

GymChal is for people **18 years and older**. It is not directed at children, including anyone under 13, and we do not knowingly collect personal data from anyone under 18. The in-app age check blocks under-18 dates of birth and does not save that information. If you believe we have collected data from someone under 18, contact us and we will delete it.

## Security

We use Firebase Authentication, access rules that limit who can read or write each kind of record, and HTTPS for network traffic. Location is requested only while the app is in use. No method of transmission or storage is perfectly secure, and we cannot guarantee absolute security.

## International processing

Our primary processing region for Firebase Authentication, Firestore, and Cloud Functions is `asia-south1` (India). Google and Apple may process limited data in other countries to provide their platforms (for example delivering an SMS one-time code, a push notification, or an App Store download), under their own terms and safeguards.

## Changes to this policy

If we change this policy, we will update the effective date on this page. For material changes we will provide a more noticeable notice where appropriate, for example in the app.

## Contact

Jalal Najafi  
Email: [najafi.jalal.cse@gmail.com](mailto:najafi.jalal.cse@gmail.com)  
Privacy Policy: [https://jalalnajafi.github.io/gymchal-legal/](https://jalalnajafi.github.io/gymchal-legal/)

This page is the Privacy Policy URL for GymChal, including App Store and TestFlight listings.
