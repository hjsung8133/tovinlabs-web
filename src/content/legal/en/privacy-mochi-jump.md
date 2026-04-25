# Mochi Jump — Privacy Policy

- **Effective Date**: [YYYY-MM-DD — to be set on launch]
- **Last Updated**: [YYYY-MM-DD — to be set on launch]
- **Operator**: tovin Labs (the "Company")
- **Service**: Mochi Jump (the "Service")

---

## 1. Scope and Child-First Principles

This Privacy Policy applies to "Mochi Jump," a child-friendly mobile game operated by the Company. The Service is designed for **children ages 7 to 13**, and the Company complies with the following laws and platform guidelines:

- **Article 22-2 of Korea's Personal Information Protection Act (special provisions for minors under 14)** and its Enforcement Decree
- The U.S. **Children's Online Privacy Protection Act (COPPA)** — protecting children under 13
- **Article 8 of the EU General Data Protection Regulation (GDPR)** — covering children between 13 and 16, depending on the member state
- Google Play's "Designed for Families" policy and the Apple App Store "Kids Category" guidelines

Where these standards differ, the Company applies the **strictest standard** to every user. The Service does not ask for or attempt to identify a user's age, and **only non-personalized advertising is shown to all users**. For users under 14, verifiable parental consent is **obtained through Apple Family Sharing or Google Family Link OS-level controls** before the child can install or use the app, and is treated as having been provided at that point.




---

## 2. Data Controller

- **Company**: tovin Labs
- **Data Protection Officer**: tovin Labs Representative
- **Contact**: privacy@tovinlabs.com

---

## 3. Information We Collect

The Company collects only the minimum information necessary, depending on how the Service is used. We do not ask for or attempt to identify any user's age, and we apply the same level of protection to every user.

### 3-1. Guest Mode Users
- Nickname (`displayName`) — entered by the user and stored only in the device's localStorage. It is never sent to our servers.

### 3-2. Registered Users
- **At sign-up**: email address, OAuth identifier (Google or Apple `sub`), nickname (`display_name`), avatar URL
- **Collected automatically during play**: score, coins earned, zone reached, play duration, total games played, personal best
- **Friends system**: friend relationships (`friend_id`, friend status)
- **Inventory and customization**: characters owned, skins, decorations, the user's selected "representative Mochi," and other in-game asset data

### 3-3. Advertising
- **Only non-personalized advertising is shown to all users.** AdMob is configured with child-directed treatment (`tagForChildDirectedTreatment(true)`) and non-personalized ads (`setNonPersonalizedAds(true)`).
- Advertising identifiers (ADID/IDFA) are used solely to deliver non-personalized ads and are never used for behavioral tracking or interest-based advertising.

### 3-4. Information We Do **Not** Collect
The Company **never** collects: real names, government ID numbers, phone numbers, postal addresses, precise location (GPS), contact lists, photos, voice recordings, biometric data, or payment card information.



---

## 4. Why We Use This Information

| Information | Purpose |
|---|---|
| Email, OAuth identifier | Account authentication, account recovery, important service notices |
| Nickname, avatar | In-game display, leaderboard listings, friends system |
| Game records (score, coins, zone, time) | Saving progress, daily rewards, achievements |
| Friend relationships | Friend invites and friend leaderboards |
| Inventory and customization | Persisting owned characters and items |
| Advertising ID | Serving non-personalized rewarded video ads (no behavioral tracking, no interest-based ads) |

---

## 5. Children Under 14 — Enhanced Protections [Important]

The Service is designed for children, and the Company has put the following enhanced safeguards in place.

### 5-1. Parental Consent — Delegated to OS-Level Controls

The Company does not ask users for their age and does not operate its own consent screen. Instead, we rely on the parental-consent infrastructure already provided by the mobile operating systems:

- **iOS**: Apple **Family Sharing**, including parent approval of downloads via "Ask to Buy" and management of the child's Apple ID
- **Android**: Google **Family Link** for parental approval of app installation, screen-time limits, and purchase controls

For users under 14, verifiable parental consent is treated as having been obtained at the moment a parent approves installation or use of the app through these OS-level controls.

### 5-2. Non-Personalized Ads for Every User

Because the Company does not identify a user's age, we follow the more conservative standard. **All users — regardless of age — see only non-personalized ads**, and advertising identifiers are never used for behavioral tracking or interest-based advertising. The following AdMob flags are applied:

- `tagForChildDirectedTreatment(true)` — COPPA compliance
- `setNonPersonalizedAds(true)` — non-personalized ads only



### 5-3. Parental Rights

A parent or legal guardian may exercise the following rights at any time by contacting privacy@tovinlabs.com:

- **Review** the personal information held about their child
- Request **correction or deletion**
- **Withdraw consent** to collection or use (by deleting the account or removing the app via OS-level parental controls)
- **Refuse** any further collection of personal information

### 5-4. Nicknames on Leaderboards and the Friends System

The user's nickname and score appear on weekly, monthly, and item leaderboards visible to other players. The Company recommends that parents choose a generic nickname for their child and avoid using a real name, school name, or other identifying details. A parent may request that their child's account be **removed from leaderboards or that the nickname be changed**, and the Company will act on such a request without undue delay.

### 5-5. Limitations of This Approach

The Company cannot fully rule out the possibility that a child under 14 may use the Service in an environment where OS-level parental controls have not been enabled. We recognize this limitation and mitigate the risk by applying the conservative standard of showing only non-personalized ads to every user. If a parent decides the Service is not appropriate for their child, they may remove the app immediately through OS settings or email privacy@tovinlabs.com to request account deletion.

---

## 6. Retention Periods

- Account information: **deleted immediately** upon account withdrawal.
- Game records: deleted immediately upon account withdrawal.
- When a parent withdraws consent, all related personal information is **deleted immediately**.
- Where a specific retention period is required by law (see Section 6.1), the affected records are stored separately for that period.

### 6.1 Retention Required by Law

Under **Article 6 of the Enforcement Decree of the Act on Consumer Protection in Electronic Commerce (Korea)** and similar provisions, the Company stores the following records separately for the periods shown below:

| Record | Retention Period | Legal Basis |
|---|---|---|
| Records relating to contracts or withdrawal of subscription | 5 years | Article 6, Enforcement Decree of the Act on Consumer Protection in Electronic Commerce (Korea) |
| Records relating to payment and supply of goods | 5 years | Article 6, Enforcement Decree of the Act on Consumer Protection in Electronic Commerce (Korea) |
| Records relating to consumer complaints or dispute resolution | 3 years | Article 6, Enforcement Decree of the Act on Consumer Protection in Electronic Commerce (Korea) |

---

## 7. Disclosure to Third Parties

The Company **does not disclose users' personal information to third parties.** However, because of the nature of the leaderboard feature, the **nickname and score a user submits are visible to other users**. This is essential to the gameplay experience, and the Company will hide a child's leaderboard entry on a parent's request.

---

## 8. Service Providers (Processors)

The Company engages the following service providers to deliver the Service:

| Provider | Role | Retention |
|---|---|---|
| Supabase Inc. | Account authentication and database hosting (AWS Tokyo region) | Until account withdrawal |
| Google LLC (AdMob) | Ad delivery — **non-personalized ads only, for every user** | At the time the ad is served |
| Apple Inc. | OAuth authentication (Sign in with Apple) | At the time of authentication |
| Google LLC | OAuth authentication (Sign in with Google) | At the time of authentication |
| Kakao Corp. | KakaoTalk friend invite / share SDK — **only triggered when the user explicitly taps a share button**, never automatically | At the time of sharing |

---

## 9. International Transfers

| Destination | Recipient | Data | Method | Purpose | Retention |
|---|---|---|---|---|---|
| Japan | Supabase Inc. (AWS Tokyo) | Email, nickname, game records, friend relationships | Encrypted HTTPS transmission | Authentication and database hosting | Until account withdrawal |
| United States | Google LLC (AdMob) | Identifiers used for non-personalized ads | Encrypted HTTPS transmission | Ad delivery | At the time the ad is served |
| United States | Google LLC / Apple Inc. | OAuth identifiers | Encrypted HTTPS transmission | Account authentication | At the time of authentication |

---

## 10. User and Parent Rights

Users — and parents acting on behalf of their children — may exercise the following rights at any time, in accordance with Articles 35–37 of Korea's Personal Information Protection Act and Section 312.6 of COPPA (parental rights):

- **Access** their personal information
- **Correct** inaccurate information
- **Delete** information (except where retention is required by law)
- **Restrict** processing
- **Withdraw consent**

To exercise any of these rights, email privacy@tovinlabs.com. The Company will respond without undue delay, and in any event within 10 days.

---

## 11. How We Delete Information

- **When**: immediately upon account withdrawal, withdrawal of consent, or expiration of the retention period.
- **How**:
  - Electronic files: permanently deleted in a non-recoverable manner (database rows removed and backups expired)
  - Device localStorage: automatically cleared by the client when the user withdraws their account
- **Separate storage**: information that must be retained by law is held in a separate database and destroyed once the legal period ends.

---

## 12. Cookies and Other Automatic Collection

The Service uses the following automatic data collection mechanisms:

- **Device localStorage** (keys prefixed with `mochiJump_`): `mochiJump_best`, `mochiJump_coins`, `mochiJump_displayName`, `mochiJump_selectedChar`, `mochiJump_unlockedChars`, `mochiJump_inventory`, `mochiJump_representativeMochi`, `mochiJump_featureFlags`, `mochiJump_locale` — used solely to save game progress on the device. None of this data is sent to our servers.
- **Advertising identifier (ADID/IDFA)**: used only to serve non-personalized ads through AdMob, and never for behavioral tracking.

Users (or their parents) can reset the advertising identifier or limit ad tracking through device settings: **iOS** → Settings > Privacy & Security; **Android** → Settings > Google > Ads.

---

## 13. Security Measures

- **Technical safeguards**: HTTPS/TLS encryption in transit, Supabase Row Level Security (RLS) policies, OAuth PKCE flow
- **Administrative safeguards**: least-privilege access to personal information, audit logging
- **Physical safeguards**: reliance on the data center security controls of our processors (Supabase / AWS Tokyo)

---

## 14. Privacy Officer

- **Privacy Officer**: tovin Labs Representative
- **Email**: privacy@tovinlabs.com

Users and parents may direct any privacy-related question or concern to the address above. The Company will respond promptly and in good faith.

---

## 15. How to Raise a Complaint

### Users in Korea
- **Personal Information Dispute Mediation Committee**: 1833-6972 (privacy.go.kr)
- **Personal Information Infringement Report Center**: 118 (privacy.kr)
- **Supreme Prosecutors' Office, Cybercrime Investigation Division**: 1301
- **National Police Agency, Cyber Bureau**: 182

### Users in the United States (COPPA)
A parent who has concerns about how their child's personal information is handled may file a complaint with the U.S. Federal Trade Commission:
- **Federal Trade Commission**, 600 Pennsylvania Avenue NW, Washington, DC 20580, USA
- **Report online**: ReportFraud.ftc.gov

---

## 16. Changes to This Policy

If this Privacy Policy is amended — whether content is added, removed, or changed — the Company will post the update inside the Service and on tovinlabs.com **at least 7 days** before it takes effect, or **at least 30 days** in advance if the change materially affects user rights.

---

*This policy was written by tovin Labs with children's safety as our highest priority. For any question about your child's use of the Service, please email privacy@tovinlabs.com.*
