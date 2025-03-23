# Apartment Management/Safety App

## Table of Contents
- [Introduction](#introduction)
- [Features](#features)
- [Hardware Requirements](#hardware-requirements)
- [Software Requirements](#software-requirements)
- [Working Principle](#working-principle)
- [Usage](#usage)
- [Future Improvements](#future-improvements)

---

## Introduction
**Apartment Management/Safety App** is an Android app I made *just for our society*—25 flats, security, and admin—to handle visitors, maintenance, and notices with a safety-first vibe. This is built for us, not for sharing outside our crew!

It runs on **Firebase** for real-time stuff and notifications, rocking a teal look with Poppins font.

---

## Features
- **Visitor Safety**: Security takes visitor pics; residents see face cards (photo + name + reason) to approve/deny.
- **Maintenance Tracking**: Residents check payment status; admin updates it.
- **Notices**: Admin posts updates; everyone sees ‘em in-app.
- **Push Notifications**: Alerts for visitor requests.
- **Easy Login**: Flat name (e.g., "Flat 24") + password.

---

## Hardware Requirements
- **Android Device**: Works on Android 5.0+ (tested on CPH1969).
- **Camera**: Security needs it for visitor pics.
- **Internet**: For Firebase sync and notifications.

---

## Software Requirements
- **Flutter SDK**: Built with Flutter 3.x.
- **Firebase**: 
  - Authentication (login).
  - Firestore (data).
  - Storage (visitor pics).
  - Messaging (notifications).
- **APK**: Use `app-release.apk`—no build needed.

---

## Working Principle
1. **Login**: 
   - Flat name (e.g., "Flat 24") + password → Firebase checks it.
2. **Visitor Flow**: 
   - Security logs visitor (name, purpose, pic) → Sends request.
   - Residents see face card → Approve/Deny.
3. **Maintenance**: 
   - Admin marks paid/unpaid → Residents see it.
4. **Notices**: 
   - Admin posts → Shows for all.

---

## Usage
1. **Get the App**: Grab `app-release.apk` from [our society’s Google Drive link].
2. **Install**: On Android, enable "Install from Unknown Sources" → Tap APK.
3. **Login**: 
   - Residents: "Flat 1" to "Flat 25", password "password123".
   - Security: "security", password "password123".
   - Admin: "admin", password "password123".
4. **Use It**: 
   - Security: Snap pics → Send requests.
   - Residents: Approve/Deny visitors.
   - Admin: Update maintenance/notices.
5. **Check**: Make sure visitors land in the right bins!

**Note**: This is custom for our society—won’t work elsewhere without tweaks!

---

## Future Improvements
- **Visitor History**: Log all past visitors.
- **Emergency Alerts**: Admin sends urgent notifications.
- **QR Codes**: Security makes QR for visitor entry.
- **Community Chat**: Residents vibe in-app.
- **Payment Proof**: Upload pics for maintenance.
