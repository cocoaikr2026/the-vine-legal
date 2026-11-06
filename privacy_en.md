---
layout: default
title: The Vine Privacy Policy
---

# The Vine Privacy Policy

Effective: 2026-11-07 · Operator: Cocoa.com (코코아닷컴) · Contact: cocoai.kr.2026@gmail.com

The Vine (the "app") is a personal journal for the wines and whiskies you drink. This policy explains what information the app handles and how. The app shows no ads, uses no analytics or tracking tools, and never sells information.

## 1. What we collect

| Kind | Items | When |
|---|---|---|
| Generated | Anonymous account identifier (random ID), adult confirmation | First launch |
| Account linking | The account identifier and email that Apple, Google or Kakao provide, and the name you choose to share with Sign in with Apple | Linking or signing in |
| Typed by you | Handle, display name, one-line bio, showcase badges, public-cellar setting | Profile settings |
| Records | Tastings (bottle, date, rating, notes, taste profile, dram and opening details), cellar (purchase date, store, price), wishlist | When you record |
| Photos | Label and receipt photos, community post photos | When you take or pick them |
| Location (optional) | One province or city code | When you allow it for the region ranking |
| Community | Posts, comments, cheers, follows, reports | When you use the community |
| Service logs | Time of AI recognition calls (daily limit), time of record and badge activity (rankings and titles) | When you use those features |

The app does not collect contacts, precise location (coordinates), advertising identifiers or device identifiers. Receipt photos are not kept after recognition.

## 2. How photos are handled

- Label and receipt photos are **sent to an external AI service** to read the bottle name and the purchase lines (Google Gemini API by default; OpenAI or Anthropic API where configured). Before sending, the app shrinks the image on the device and strips metadata such as location (EXIF). The provider receives the photo only to answer the request; the app uses API terms under which the provider does not train on it.
- **Label photos of bottles not yet in the catalogue are kept for review.** Only a curator sees them, when adding that bottle to the catalogue; other users never do. They are deleted with your account.
- Receipt photos are used for recognition only and are not stored on the server.
- Post photos are **public** in the community. Metadata is stripped before upload.
- A numeric fingerprint derived from a label photo (numbers, not the image) helps recognise the same bottle again; after account deletion it may remain with no link to you.

## 3. Why we use it

- Storing records, cellar and wishlist and syncing them between devices
- Computing the experience and explore screens (countries, grapes, map, dex) and badges, levels, weekly goals
- Label and receipt recognition and bottle information
- Running the community (boards, comments, rankings, profiles) and handling reports
- Preventing abuse, such as the daily AI limit
- Answering enquiries and meeting legal obligations

## 4. How long we keep it

- For as long as your account exists. **Deleting the account removes everything from our servers at once** (Settings › Account › Delete Account). Anonymous accounts are treated the same way.
- Backup copies are removed in turn according to the hosting provider's retention cycle.
- Records of an anonymous account that was never linked cannot be reached after a phone change or an uninstall, and the operator cannot recover them.

## 5. Third parties and processors

We do not sell information or share it for advertising. These companies process information as needed to run the service:

| Company | Role | Information | Location |
|---|---|---|---|
| Supabase, Inc. | Database, file storage and authentication hosting | Everything in section 1 | Servers in Seoul, Korea (AWS ap-northeast-2); the company is in the US |
| Google LLC (Gemini API) | Label and receipt photo recognition | Photos, recognised text | Abroad (US) |
| OpenAI / Anthropic (where configured as the fallback provider) | Same | Photos, recognised text | Abroad (US) |
| Apple, Google, Kakao | Sign-in providers | Account identifier, email, name (optional) | Per each company's terms |

Photo recognition and the sign-in providers process data abroad (international transfer); the database is in Seoul. Everything is encrypted in transit. We may disclose information where the law requires it.

## 6. Your rights

- Access and correction: you see and edit your records and profile inside the app.
- Deletion: Settings › Account › **Delete Account** removes everything at once. Individual records, posts and comments can be deleted in the app too.
- Location: the region ranking's location use can be changed or refused at any time.
- For anything else, write to cocoai.kr.2026@gmail.com; we answer within 10 days.

## 7. Minors

The app is for adults only (19+ in Korea, the legal drinking age elsewhere) and asks for confirmation on first launch. If we learn that a minor's information was collected, we delete it.

## 8. Security

- Encryption in transit (TLS), least-privilege access to storage
- Row-level access control in the database: only you can read and write your records; others see only what you made public.
- Prices, stores and notes stay private even when your cellar is public.
- No passwords. Sign-in happens only through Apple, Google or Kakao.

## 9. Cookies, tracking, ads

The app uses no cookies, advertising identifiers, third-party analytics SDKs or push notification tokens.

## 10. Changes

Changes appear in this document inside the app and at the public URL, with a new effective date. Material changes are announced in the app.

## 11. Privacy officer

- Operator: Cocoa.com (코코아닷컴)
- Email: cocoai.kr.2026@gmail.com

Questions, complaints and requests about this policy go to the contact above. Residents of Korea may also contact the Personal Information Infringement Report Center (privacy.kisa.or.kr, 118).
