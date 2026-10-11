# Word Quest â€” Privacy Policy

**Last updated:** 11 October 2026

## 1. Who we are

"Word Quest" ("we", "us", "our") is a free word puzzle game made
by Sajib. This policy explains what data is stored or processed when you
play, and how you can control it.

There are two separate things to understand:

- **(a) Game data** (levels, coins, settings) is stored **only on your
  device** by us and is never sent to us.
- **(b) Advertising** is handled by a third-party SDK, the
  **Google Mobile Ads SDK (AdMob)**, integrated in the Android app. When
  an ad is requested, data is processed by **Google** as described in
  Section 3. We do not control Google's servers or retention.

We do **not** operate accounts, we do **not** ask for your name, email
address, or other contact details inside the app, and we do **not**
integrate analytics or crash-reporting SDKs.

## 2. Game data we store on your device (never leaves the device)

| Data | Why it is stored | Where it lives | Can you delete it? |
|---|---|---|---|
| Game progress â€” completed levels, coins, hints used, current level | To let you keep playing without re-doing levels | LocalStorage on the device | Yes. Settings â†’ "Reset progress" deletes everything, or uninstall the app. |
| Sound / motion preferences | To remember your chosen settings | LocalStorage on the device | Yes. Change the toggle in Settings, or use "Reset progress". |

Our code does **not** collect your name, email, phone number, address,
payment information, location, contacts, camera, microphone, photos,
browsing history, or app-usage analytics, and it sends **no game data**
to us or to anyone else. One platform caveat: the Android manifest leaves
`android:allowBackup` enabled, so Android's own device backup (if you have
it turned on) may copy app data according to your device and backup
settings — that copy is controlled by Android/Google, not collected by us.

## 3. Advertising (Google Mobile Ads SDK / AdMob)

The Android app integrates the **Google Mobile Ads SDK (AdMob)** to show a
bottom banner and full-screen interstitial ads (on paid Hints and on level
completion). The app currently uses **Google's official test ad units**,
but the SDK is real: whenever an ad is requested, **data is processed by
Google** to deliver the ad, which can include device information and the
Android advertising ID supplied by the operating system.

What this means in plain terms:

- **We do not receive, see, or store any advertising data.** Your game
  progress is never sent to Google or to any advertiser.
- **Google processes ad-request data on its own systems** under Google's
  own privacy policy
  ([Google Privacy Policy](https://policies.google.com/privacy) and
  [Google's publisher data information](https://business.safety.google/privacy/)).
  We cannot describe, limit, or delete what Google retains â€” only Google can.
- You can limit ad personalisation and reset the identifier from the
  device: Android Settings â†’ Google â†’ Ads (opt out of personalised ads /
  reset advertising ID). Steps vary by Android version.

If production ad units are ever enabled, this policy will be updated before
release to describe the live configuration.

## 4. Sharing and disclosures

- We do **not** sell, trade, or share your game data with anyone. It never
  leaves your device.
- We do **not** use analytics or crash-reporting SDKs.
- When the AdMob SDK requests an ad, Google processes ad-request data as
  described in Section 3. That processing is governed by Google's policies,
  not by ours, and we receive none of it.
- We will disclose data only if required by law, and only to the extent
  the law requires. Such a request could only concern data we actually
  hold â€” which, for game data, is nothing, because it stays on your device.

## 5. Children's privacy (all ages, including children)

Word Quest is a general word puzzle game intended for **all ages,
including children**. We do not ask children (or anyone) for names,
contact details, or any other personal information inside the app, and
our code stores only local game progress.

However, because the app integrates the **Google Mobile Ads SDK**, ad
requests are processed by Google as described in Section 3. Parents and
guardians should be aware of this, and should know that:

- Google Play's **Families / target-audience declaration** and the app's
  **content rating** for this app have **not yet been completed or
  verified** â€” those store declarations must be finished before any
  public release, and this policy must not be read as proof of
  Families-policy compliance.
- If you are a parent or guardian and believe ad-related data about your
  child has been processed by Google in connection with this app, please
  contact Google under its own policies, and contact us (Section 9) so we
  can consider what app-side steps are available.

## 6. Data retention and deletion (what we can and cannot promise)

- **Game data (our side):** kept on your device until you delete it.
  Settings â†’ "Reset progress" deletes all levels, coins, and preferences
  immediately; uninstalling the app removes it too. Because it never
  reaches our servers, there is nothing for us to retain afterwards and
  nothing we could recover.
- **Advertising data (Google's side):** we hold no copy and operate no
  deletion queue for it. How long Google retains ad-request data, and what
  deletion or objection rights apply to it, is determined by Google's own
  policies â€” we cannot promise deletion of data we never receive. Resetting
  or opting out via Android Settings â†’ Google â†’ Ads limits future
  personalisation but does not delete Google's past records; see Google's
  documentation for what that control does.

## 7. Changes to this policy

If we change how data is handled, we will post the new version here and
update the "Last updated" date. For significant changes we will make that
clear in the app. The current published build uses test ad units; enabling
live production ads or adding any consent mechanism would be a significant
change disclosed here first.

## 8. Regional notes (no compliance outcome claimed)

- **EU/EEA/UK:** game progress is stored on-device as strictly necessary
  to provide the game you asked for. Whether any consent mechanism is
  required for the Google Mobile Ads SDK in your region has **not been
  determined or implemented in this build** — no consent banner exists yet,
  and this policy does not claim GDPR/ePrivacy consent compliance.
- **California (CCPA/CPRA):** we do not sell or share your game data.
  Deleting it is done on-device via "Reset progress" or uninstall. Rights
  concerning ad-request data held by Google must be directed to Google.

## 9. Contact

If you have questions about this policy, email
**[tanmoyraj31@gmail.com](mailto:tanmoyraj31@gmail.com)**.

## 10. Cookies, local storage, and third-party links

Game progress and settings live in the device's LocalStorage (key
`wordquest:progress`). The app sets **no advertising or tracking cookies
of its own**; any identifiers or storage used for ad delivery belong to
Google's SDK and are governed by Google's policies, not ours.

Word Quest may contain links to other websites. This policy applies only
to Word Quest. We are not responsible for the privacy practices of
third-party sites.
