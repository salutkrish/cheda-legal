# Cheda — Privacy Policy

**Last updated:** 6 October 2026  
**Operator:** Dhaarana Holdings Pty Ltd  
**Product:** Cheda (desktop application)

## 1. Summary

Cheda is a **local** desktop app. Media files, drafts, post history, and encrypted credentials are stored on **your device**. Cheda is not a cloud host for your videos.

## 2. Data Cheda stores on your device

Depending on how you use the app, Cheda may store locally:

- Paths and metadata for imported videos (duration, size, thumbnails, content hashes)
- Draft captions, hashtags, and per-platform options
- Post attempt history and analytics snapshots you refresh
- OAuth tokens and developer client secrets, encrypted with your OS keyring via Electron `safeStorage`
- App settings (for example Google Drive folder IDs)

This data stays under your user profile on the machine (for example `~/.config/cheda` on Linux) unless you copy or back it up elsewhere.

## 3. Data sent to third parties

Cheda only contacts third parties when you take an action that requires it, for example:

- **Google / YouTube / Google Drive** — when you Connect, import/export Drive files, or publish after Confirm
- **TikTok** — when you Connect or publish after Confirm

Those services receive what their APIs require for that action (tokens, video bytes, captions, privacy settings you chose). Their processing is governed by **their** privacy policies.

## 4. What we do not do

- We do not auto-post because a file appeared in a folder
- We do not sell your content or credentials
- We do not require a Cheda cloud account for core local use

## 5. Your choices

- Disconnect platforms in Settings to revoke app access (also revoke in the platform’s security settings if you want)
- Delete local app data by removing Cheda’s config/data directory on your machine
- Avoid connecting a platform if you do not want that integration

## 6. Children

Cheda is intended for adults and creators who can form contracts and comply with platform rules. It is not directed at children.

## 7. Changes

We may update this Privacy Policy. The “Last updated” date will change when we do. Continued use after an update means you accept the revised policy.

## 8. Contact

For privacy questions about Cheda, contact the operator via the Dhaarana Holdings Pty Ltd / Cheda project maintainer channels you already use.
