---
layout: default
title: Privacy Policy — Discover
---

# Privacy Policy

**Discover**
**Last updated: March 17, 2026**

## Introduction

Discover ("we," "our," or "the app") is a place discovery app that lets you swipe through restaurants and venues, save your favorites, and get directions. This Privacy Policy explains what information we collect, how we use it, and your choices.

By using Discover, you agree to the practices described in this policy. If you do not agree, please do not use the app.

## Information We Collect

### Information You Provide

- **Account information.** When you create an account, we collect your email address and a password (for email sign-up) or receive an authentication token from Google (for Google Sign-In). If you sign in with Google, we receive your email address and display name from your Google account.
- **Bug reports.** If you submit a report through the "Report a Problem" form, we collect your name, email address, and the message you write, along with your account ID so we can follow up.

### Information Collected Automatically

- **Location data.** With your permission, we access your device's approximate location to calculate distances between you and nearby places. Location is determined using your device's GPS, cached locally for up to 5 minutes, and is **not** stored on our servers.
- **Swipe history.** When you swipe left (skip) on a place, the place ID and timestamp are stored locally on your device for 3 days so you don't see the same place again. This data is never sent to our servers.
- **Search history.** The last 3 cities you searched are stored locally on your device so you can quickly re-select them. This data is never sent to our servers.
- **Saved places.** When you swipe right (save) on a place, the place details (name, address, type, photo reference) are stored in your private Firestore account so they sync across devices.
- **Subscription status.** We use RevenueCat to manage in-app subscriptions. RevenueCat records your purchase history and entitlement status, linked to your account ID.
- **Usage analytics.** Firebase may collect basic analytics data such as app opens, crashes, and performance metrics. This data is anonymized and used solely to improve app stability.

### Information We Do Not Collect

- We do not collect or store your precise GPS coordinates on our servers.
- We do not track your browsing activity outside the app.
- We do not collect contacts, photos, or other personal files from your device.
- We do not serve ads or share data with advertising networks.

## Third-Party Services

Discover relies on the following third-party services, each with their own privacy policies:

| Service | Purpose | Privacy Policy |
|---|---|---|
| **Firebase (Google)** | Authentication, database (Firestore), App Check | [firebase.google.com/support/privacy](https://firebase.google.com/support/privacy) |
| **Google Places API** | Place data (names, photos, addresses, ratings) | [cloud.google.com/maps-platform/terms](https://cloud.google.com/maps-platform/terms) |
| **Google Sign-In** | OAuth authentication | [policies.google.com/privacy](https://policies.google.com/privacy) |
| **RevenueCat** | Subscription and purchase management | [revenuecat.com/privacy](https://www.revenuecat.com/privacy) |

We do not sell, rent, or share your personal information with third parties for their marketing purposes.

## How We Use Your Information

We use the information we collect to:

- Provide and maintain the app's core functionality (account management, place discovery, saving places, directions).
- Calculate distances to places based on your location.
- Process and manage your subscription.
- Respond to bug reports and support requests.
- Improve app performance and fix crashes.

## Data Storage and Security

- **Account and saved places** are stored in Google Cloud Firestore. Each user's data is isolated using Firestore security rules that restrict access to the authenticated account owner only.
- **Local data** (swipe history, search history, swipe counts) is stored on your device using SharedPreferences and is never transmitted to our servers.
- **API requests** to Google Places are proxied through Firebase Cloud Functions so that API keys are never exposed on the client device.
- **Firebase App Check** is enabled to prevent unauthorized access to our backend services.

While we take reasonable measures to protect your data, no method of electronic storage or transmission is 100% secure.

## Data Retention

- **Account data and saved places** are retained as long as your account exists.
- **Bug reports** are retained as long as needed to resolve the reported issue, then deleted.
- **Local swipe history** expires automatically after 3 days.
- **Local search history** stores a maximum of 3 recent cities and is cleared on sign-out.

## Your Rights and Choices

- **Access your data.** Your saved places and account information are visible within the app at all times.
- **Delete your account.** You can permanently delete your account and all associated data from Settings → Manage Account → Delete Account. This removes your Firestore data, clears local storage, and deletes your Firebase Auth account.
- **Location permissions.** You can grant or revoke location access at any time through your device's system settings. The app functions without location access, but distance information will be unavailable.
- **Sign out.** Signing out clears your local caches and search history for your account.

## Children's Privacy

Discover is not directed at children under 13. We do not knowingly collect personal information from children under 13. If we become aware that we have collected data from a child under 13, we will delete that information promptly.

## Changes to This Policy

We may update this Privacy Policy from time to time. When we do, we will update the "Last updated" date at the top of this page. We encourage you to review this policy periodically.

## Contact Us

If you have questions or concerns about this Privacy Policy, please contact us at:

**Email:** jeremysiu3@gmail.com

---

*This privacy policy applies to the Discover mobile application, available on the Apple App Store and Google Play Store.*
