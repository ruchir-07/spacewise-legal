# SpaceWise — Privacy Policy

**Last updated: 30 July 2026**

SpaceWise is a storage cleaner and document organiser that runs entirely on your
phone. This policy describes what the app does with your information. It is
short because the app collects almost nothing.

---

## The short version

**SpaceWise has no accounts, no servers and no analytics.** Your photos, videos,
contacts and documents never leave your device. There is no login, nothing to
sign up for, and no way for us to see your data — we do not operate a backend
that could receive it.

The single exception is purchases, which are handled by Apple, Google and
RevenueCat. That is described in full below.

---

## What SpaceWise accesses on your device, and why

SpaceWise asks for these permissions only when you use the feature that needs
them, and each one is used strictly on-device:

| Permission | Why | Leaves your device? |
|---|---|---|
| **Photo library** | Find similar photos, duplicate videos, screenshots, blurry shots and large files; move photos you choose into the Vault | **No** |
| **Save to photo library** | Put a photo back when you restore it from the Recycle Bin or the Vault | **No** |
| **Camera** | Photograph receipts and documents to scan | **No** |
| **Contacts** | Find duplicate contact cards and, when you tap Merge, combine them | **No** |
| **Face ID / fingerprint** | Unlock your private Vault | **No** |
| **Notifications** (optional) | Local reminders such as "items in your Recycle Bin expire in 3 days" | **No** |

All analysis — duplicate detection, blur detection, and reading text from your
receipts — happens using your phone's own processor. No image, contact,
document or piece of text is transmitted anywhere.

## What SpaceWise does NOT collect

- No account, email address, name or phone number
- No advertising identifiers; **no ad SDKs are bundled in the app**
- No location data; the app never requests location permission
- No usage analytics, telemetry, crash reporting or behavioural tracking
- No browsing history or data from other apps
- No photos, videos, contacts, documents or extracted text

There is no code path in SpaceWise that uploads your content. This is not a
promise about how we behave — the capability is simply not in the app.

## Data stored on your device

SpaceWise saves the following locally, and only locally:

- Your settings and preferences
- Your scanned documents and their extracted fields
- Items in the Recycle Bin (kept for 30 days, then removed)
- Files you move into the Vault, held in private app storage
- Your Vault PIN, stored **only as a salted SHA-256 hash** in your device's
  keychain/keystore — never in plain text, and it cannot be turned back into
  your PIN
- A daily record of how much free space your device has, used to draw your
  storage trend

Uninstalling SpaceWise removes all of it. We keep no copy, because we never
receive one.

### What the Vault does and does not protect

When you move a photo into the Vault, SpaceWise copies it into private app
storage and deletes the original from your photo library, so it no longer
appears in Photos, in shared albums, or in any scan.

It does **not** protect against someone using your phone while it is unlocked
with the Vault already open, a full device backup taken on a computer, or a
rooted/jailbroken device with a file browser. Vaulted files rely on your
operating system's own disk encryption; they are private, not separately
encrypted.

## Purchases

If you buy SpaceWise Pro, the transaction is processed by **Apple's App Store**
or **Google Play**. We never see or receive your card details.

We use **RevenueCat** to verify and restore purchases. When you buy or restore,
RevenueCat receives your purchase receipt and an anonymous, randomly generated
app-user ID, plus basic device/platform information needed to validate the
purchase. It does **not** receive your name, email, photos, contacts or
documents.

- RevenueCat privacy policy: https://www.revenuecat.com/privacy
- Apple privacy policy: https://www.apple.com/legal/privacy/
- Google privacy policy: https://policies.google.com/privacy

If you never make a purchase, no purchase data is created and nothing is sent
to RevenueCat.

## Children

SpaceWise is not directed at children and does not knowingly collect any
information from anyone, including children.

## Your rights

Because SpaceWise stores your data only on your own device:

- **Access / export:** your documents can be exported to CSV or PDF from within
  the app at any time.
- **Deletion:** delete items in the app, or uninstall it to remove everything.
- We cannot delete data on your behalf, because we never hold any.

For purchase records, contact Apple, Google or RevenueCat using the links above.

## Changes to this policy

If this policy changes, the updated version will be published at this URL with a
new "Last updated" date. If SpaceWise ever adds anything that collects data —
for example optional crash diagnostics — it will be listed here first, disclosed
in the app's Privacy Report screen, and switchable off in Settings.

## Contact

Questions about this policy: **rbscoop2611@gmail.com**
