# kept. — Privacy Policy

**Last updated: 6 November 2026**

kept. (formerly SpaceWise) is a storage cleaner and document organiser that runs entirely on your
phone. This policy describes what the app does with your information. It is
short because the app collects almost nothing.

---

## The short version

**kept. has no accounts, no analytics, and no backend that can receive your
content.** Your photos, videos, contacts and documents never leave your device.
There is no login and nothing to sign up for.

kept. is free. There is nothing to buy, no ads, and no locked features.

The app makes exactly **one** kind of network request, and it does not carry
your content: an **app-update check** against Expo's update service on launch.
That is described in full below.

---

## What kept. accesses on your device, and why

kept. asks for these permissions only when you use the feature that needs
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

## What kept. does NOT collect

- No account, email address, name or phone number
- No advertising identifiers; **no ad SDKs are bundled in the app**
- No location data; the app never requests location permission
- No usage analytics, telemetry, crash reporting or behavioural tracking
- No browsing history or data from other apps
- No photos, videos, contacts, documents or extracted text

There is no code path in kept. that uploads your content. This is not a
promise about how we behave — the capability is simply not in the app.

## App updates

kept. can deliver bug fixes without waiting for a store review. To do that,
on launch the app asks Expo's update service (`u.expo.dev`) whether a newer
version of its own JavaScript is available.

That request contains only what is needed to answer the question — the app's
version, the platform it is running on, and which release channel it is on. As
with any internet request, Expo's servers can see the IP address it came from.

**No information about you, your files, your contacts or your usage is included
in that request**, and nothing about your device's contents is sent. If you
would rather the app never made it, turning off "Background App Refresh" and
using the app offline prevents it; every feature works with no connection.

Expo's own privacy policy: https://expo.dev/privacy

## Data stored on your device

kept. saves the following locally, and only locally:

- Your settings and preferences
- Your scanned documents and their extracted fields
- Items in the Recycle Bin (kept for 30 days, then removed)
- Files you move into the Vault, held in private app storage
- Your Vault PIN, stored **only as a salted SHA-256 hash** in your device's
  keychain/keystore — never in plain text, and it cannot be turned back into
  your PIN
- A daily record of how much free space your device has, used to draw your
  storage trend

Uninstalling kept. removes all of it. We keep no copy, because we never
receive one.

### What the Vault does and does not protect

When you move a photo into the Vault, kept. copies it into private app
storage and deletes the original from your photo library, so it no longer
appears in Photos, in shared albums, or in any scan.

It does **not** protect against someone using your phone while it is unlocked
with the Vault already open, a full device backup taken on a computer, or a
rooted/jailbroken device with a file browser. Vaulted files rely on your
operating system's own disk encryption; they are private, not separately
encrypted.

## Purchases

**There are none.** kept. is free, every feature is unlocked, and the app
contains no in-app purchases and no ads. No payment processor is contacted and
no purchase data of any kind is created.

If a paid version is ever added, this policy will be updated first, and the
change will be described here before it ships.

## Children

kept. is not directed at children and does not knowingly collect any
information from anyone, including children.

## Your rights

Because kept. stores your data only on your own device:

- **Access / export:** your documents can be exported to CSV or PDF from within
  the app at any time.
- **Deletion:** delete items in the app, or uninstall it to remove everything.
- We cannot delete data on your behalf, because we never hold any.

There are no purchase records to request, because the app sells nothing.

## Changes to this policy

The published copy of this policy lives at https://ruchir-07.github.io/spacewise-legal/privacy.html — that is the URL given to
the App Store and Google Play.

If this policy changes, the updated version will be published at that URL with a
new "Last updated" date. If kept. ever adds anything that collects data —
for example optional crash diagnostics — it will be listed here first, disclosed
in the app's Privacy Report screen, and switchable off in Settings.

## Contact

Questions about this policy: **rbscoop2611@gmail.com**
