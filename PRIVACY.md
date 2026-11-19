# UnaCleaner — Privacy Policy

**Effective Date:** October 25, 2026  
**Last Updated:** November 19, 2026

**UnaCleaner** (for macOS, iOS, and iPadOS) is developed by **Rareș-Mihail Cristea** with a strict commitment to user privacy and 100% local-first software architecture.

---

## 1. Zero Data Collection (`Data Not Collected`)

**UnaCleaner does not collect, transmit, store on external servers, sell, or share any personal data.**

- **No Personal Information Collected**: We do not collect names, email addresses, phone numbers, IP addresses, location data, or device identifiers.
- **100% On-Device File, Photo & Contact Processing**: All file scans, SHA-256 duplicate checks, Apple Vision photo quality scoring, HEVC video compression, Live Photo conversion, and Contacts duplicate merging & local `.vcf` vCard backups execute strictly on your local device.
- **Zero Third-Party Telemetry or SDKs**: UnaCleaner contains zero third-party analytics SDKs, zero advertising networks, and zero remote telemetry probes.

---

## 2. In-App Purchases and Subscriptions (StoreKit 2)

In-app purchases (**UnaCleaner Lifetime License** — `com.UnaCleaner.app.lifetime`) and auto-renewable subscriptions (**UnaCleaner Annual Plan** — `com.UnaCleaner.app.sub.annual`) are processed directly and exclusively by Apple via **StoreKit 2**:
- All payment transactions, receipts, free trials, and renewals are handled by Apple's secure servers in accordance with the [Apple Privacy Policy](https://www.apple.com/legal/privacy/) and [Standard Apple EULA](https://www.apple.com/legal/internet-services/itunes/dev/stdeula/).
- UnaCleaner verifies Apple's cryptographically signed StoreKit 2 JWS transaction state locally on your device.

---

## 3. App Sandbox & System Permissions

UnaCleaner adheres strictly to the **Apple App Sandbox** on macOS and iOS:
- **macOS Folder Access**: Requested explicitly via standard macOS open panels and persisted locally via security-scoped bookmarks.
- **Photo Library**: Used solely on-device to identify similar photos, screenshots, Live Photos, and large videos for user-confirmed cleanup or compression.
- **Contacts**: Used solely on-device to detect duplicate or incomplete contacts, create local `.vcf` safety backups, and merge duplicates upon confirmation.
- **Face ID / Touch ID**: Used solely on-device via `LocalAuthentication` to protect biometric privacy controls.

---

<a id="user-privacy-choices"></a>
## 4. User Privacy Choices & Contact Information

Because UnaCleaner collects zero personal data on external servers, no remote profile or cloud record exists:
- You retain 100% local control over all scans, selections, backups, and deletions.
- You can revoke Photo Library, Contacts, or Folder permissions anytime in **macOS System Settings → Privacy & Security** or **iOS Settings → UnaCleaner**.

For privacy, compliance (GDPR / CCPA / EU GPSR / DSA), or support inquiries:
- **Developer**: Rareș-Mihail Cristea
- **Email**: [rares.cristea@ymail.com](mailto:rares.cristea@ymail.com)
- **Support Page**: [https://raresmihailcristea-cmyk.github.io/unacleaner-public/support.html](https://raresmihailcristea-cmyk.github.io/unacleaner-public/support.html)
