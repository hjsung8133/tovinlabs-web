# tovin Labs Kids Policy

- **Effective date**: [YYYY-MM-DD — to be set on launch]
- **Last updated**: [YYYY-MM-DD — to be set on launch]
- **Operator**: tovin Labs (the "Company", "we", or "us")
- **About this document**: This Kids Policy supplements our Privacy Policy. It is written for parents, legal guardians, and teachers, so you can feel confident before letting a child you care for play one of our games.

---

## 1. Why this policy exists — our promise to parents

When a child is having fun in one of our games, you should be able to see clearly what happens with their information. This policy explains, in plain language, **what we do not collect**, the safeguards that are always switched on, and the rights you have as a parent.

We hold ourselves to five basic promises:

1. We do **not** collect a child's real name, phone number, precise location, photos, or voice.
2. Children **never** see personalized (behavioral) ads in our apps.
3. The app does **not** ask users their age directly. Instead, we rely on **parental consent provided through the operating system** (Apple Family Sharing, Google Family Link, etc.).
4. You can ask us at any time to **see, delete, or stop processing** your child's data.
5. If we change anything important in this policy, we will **notify you inside the app and update this page** before the change takes effect.

---

## 2. Who this policy applies to

This policy applies to **Mochi Jump** — a casual endless-jump game rated for everyone. Mochi Jump enforces child-safety policies (COPPA, GDPR-K) so the experience remains safe for children. Our other app, **Kotoba** (a language-learning app), is intended for users 14 and older, so this Kids Policy has only very limited relevance there.

Whenever we say "child" or "children" in this document, we generally mean a user **under 14**. In practice, we apply the **strictest** of the following frameworks to every child user, regardless of where they live:

- **COPPA** (United States — Children's Online Privacy Protection Act, applies under 13)
- **GDPR-K** (European Union — child-specific provisions, applies between 13 and 16 depending on member state)
- **Article 22-2 of Korea's Personal Information Protection Act** (special provisions for minors under 14)

---

## 3. How we get parental consent — we trust your device's parental controls

We do not run our own separate consent flow for users under 14. Instead, we rely on the **parental consent you have already set up through your child's device** (smartphone or tablet).

> **Mochi Jump does not ask users for their age. If a child under 14 is going to use the app, parental consent must already be in place at the operating-system level — for example through Apple Family Sharing or Google Family Link.**

When you link your child's Apple ID or Google account into your family group and approve permission for them to download, install, or make purchases in Mochi Jump, we treat that approval as the parental consent required by this policy. This is the approach recommended by Apple's "Kids Category" guidelines and Google Play's "Designed for Families" program.

If a child installs and uses the app under an adult account without parental supervision, the responsibility under this policy lies with the account holder. We trust that when an app is installed under a child's account, the appropriate parental approvals have been granted on the device.

---

## 4. What we collect (at a glance)

For full details, please see the **Mochi Jump Privacy Policy**. The summary below is for quick reference.

**What we do collect**

- **Nickname** — entered by the user. It does not need to be a real name; we recommend a fun, generic nickname.
- **Game activity data** — score, play time, zones reached, coins earned, and similar gameplay information.
- **Advertising identifier** — used **only for non-personalized advertising**, for purposes such as ad frequency capping and click-fraud prevention.

**What we do NOT collect**

- Real name, national ID, or any other identity document information
- Home address or phone number
- Precise location (no GPS)
- Photos or videos (we do not request camera or photo-library permission)
- Voice recordings (we do not request microphone permission)
- Contacts, calendar, or any other personal data on the device

---

## 5. Advertising — children do not see "ads that follow them around"

Every ad shown in Mochi Jump is a **non-personalized ad**.

- We use Google AdMob's `tagForChildDirectedTreatment(true)` and `setNonPersonalizedAds(true)` settings, so ads are not tailored to a user's behavioral history. *(Note: this code-level flag is in the process of being applied across all ad placements.)*
- The advertising identifier (ADID/IDFA) is **not** used to track behavior or build advertising profiles. It is used only for technical purposes such as frequency capping.
- Ads are limited to **one or two rewarded ads per game session**. We do not use forced full-screen interstitials that interrupt children repeatedly.

We also list Mochi Jump in Apple's "Made for Kids" category and Google Play's "Designed for Families" program, so the platforms' own children's-advertising policies apply on top of ours.

---

## 6. Friends and leaderboards — what other players can see

Mochi Jump includes a friend-add feature and a leaderboard (high-score ranking).

- **Nicknames are visible to other players** — they appear, alongside scores, on the leaderboard and in friend lists.
- **A note for parents**: please help your child choose a **generic nickname** (for example, "JumpingBunny") that does not reveal their real name or school.
- The friend feature can be **turned off** at any time. From the in-app settings, you can disable incoming friend requests or make the friend list private.
- Sharing to outside services such as Kakao only happens when the **user actively taps a share button**. Nothing is shared in the background or automatically.

---

## 7. Your rights as a parent or legal guardian

You have the following rights over your child's data:

- **Access** — request a copy of the data we hold for your child's account.
- **Deletion** — ask us to delete some or all of your child's data.
- **Withdraw consent** — revoke app permissions through your device's parental controls, or use the in-app account-deletion menu.
- **Correction** — ask us to correct any information that is inaccurate.

To exercise any of these rights, please email **privacy@tovinlabs.com** with your child's account email or nickname and your request. We will respond within **7 business days**. To verify your identity, we may need to ask for additional information confirming the parent-child relationship.

---

## 8. How long we keep data

- When an account is deleted, or when a parent requests deletion, ordinary information is **deleted immediately**.
- A few specific items must be kept longer because the law requires it (for example, payment and refund records, under Korea's e-commerce consumer protection statute). These items are kept separately for the legally required period and then destroyed.
- Game progress data (scores, play history, etc.) is kept while the account is active and is deleted together with the account.

---

## 9. Third-party tools we use

We use a small set of carefully chosen tools to run the service. Each one is contractually bound to follow our policies, and we apply additional safeguards where children are involved.

| Tool | Purpose | Child-specific safeguard |
|---|---|---|
| Google AdMob | Serving ads | Child-directed treatment (`tagForChildDirectedTreatment`), non-personalized ads only |
| Supabase | Game records and account storage (AWS Tokyo region) | Encryption in transit and at rest, restricted access controls |
| Kakao | Friend invites and sharing | Called **only when the user actively taps a share button** |

---

## 10. International transfers

Some data is transferred outside Korea in the normal course of running the service:

| Recipient | Country | Data transferred | When and how | Retention |
|---|---|---|---|---|
| Google LLC (AdMob) | United States | Advertising identifier (non-personalized), device information | Transmitted over HTTPS when an ad is requested | Per Google's policy |
| Supabase Inc. (AWS Tokyo) | Japan | Nickname, game records, friend relationships | Transmitted over HTTPS during normal app use | Until the account is deleted |

If you do not consent to your child's data being transferred internationally, the service may not be available. Please contact privacy@tovinlabs.com to let us know.

---

## 11. Security measures

- All communication uses HTTPS (TLS) encryption.
- Server databases are accessible only to a small number of authorized personnel, and access is logged.
- We carry out regular security reviews and apply patches promptly.
- Children's data is **not** used for marketing or profiling of any kind.

---

## 12. Letting you know about changes

If we make a meaningful change to this policy (for example, adding a new data category or a new third-party tool), we will tell you in advance:

- An in-app notice (announcement or popup) at least **7 days before** the change takes effect.
- An update to the "Last updated" date at the top of this page.
- For more significant changes, we may also reach out through the parent contact channel provided at sign-up.

If you do not agree to a new version of the policy, you can delete your child's account or revoke the app's permission through your device's parental controls.

---

## 13. Contact us

- **Business name**: Tovin Labs
- **Representative**: SUNG HYUN JOON
- **Business Registration Number**: 386-24-02209
- **Business address**: 50-20 Dolmun-ro, Gimpo-si, Gyeonggi-do, 10108, Republic of Korea
- **Website**: https://tovinlabs.com
- **Privacy contact**: privacy@tovinlabs.com
- **Phone**: +82-10-5751-8133

We answer every parent inquiry personally. Building a service your child can enjoy safely is the most important responsibility we have.

---

**Effective date**: [YYYY-MM-DD — to be set on launch]
