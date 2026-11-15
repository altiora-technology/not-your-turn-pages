# Not Your Turn: Privacy Policy

**Last updated: 15 November 2026**

This policy explains what personal information the Not Your Turn app collects, why, who it goes
to, how long it is kept, and what you can do about it. It applies to the Not Your Turn app for
Android and to the server the app talks to.

## 1. Who we are

Not Your Turn is made by **Tim Cooley, a sole trader trading as Altiora Technology**, based in
England. The address for post is **19 The Sidings, Bishops Itchington, Southam, CV47 2EJ**.

Tim Cooley, trading as Altiora Technology, is the "controller" of the personal information
described here, which means we decide how and why it is used.

Contact for anything about your data, including requests under section 8:
**support@altiora-technology.co.uk**

We are registered with the Information Commissioner's Office, registration number
**ZC296524**.

We have not appointed a Data Protection Officer; we are not required to.

## 2. The short version

- You sign in with Google, Microsoft or Facebook. We get your name, an identifier for your
  account with that provider, and usually your email address. We never see your password.
- We keep what you and your household put into the app: the household's name, its chores, who did
  what and when, and the nudges and reminders sent.
- If you allow notifications, we keep a token that lets us send notifications to your phone.
- If you pay for Plus, the payment is handled by Stripe. We never see your card details.
- We do not show adverts, we do not sell your data, and the app contains no analytics or
  tracking.
- You can delete your account from inside the app at any time (Household tab, "Delete my
  account"), or by emailing us.

## 3. What we collect, and where it comes from

### 3.1 From your sign-in provider, when you sign in

| What | Notes |
|---|---|
| Your name | As your provider gives it. Shown to the other members of your household. |
| Your email address | From Google and Microsoft. Facebook sign-in in this app asks only for your public profile, so we normally get no email address from Facebook. |
| Whether the provider says the email address is verified | Used to decide whether two sign-ins (for example Google and Microsoft) with the same verified address belong to the same person, so they share one account. |
| Your provider and your account identifier with it | For example "google" and a long number. This is how we recognise you next time. |
| A link to your profile picture | Google only. |
| When your account was created and when you last signed in | |

We do not receive your password or anything else from your account with the provider.

### 3.2 What you and your household put into the app

| What | Notes |
|---|---|
| Household name, time zone, members and who is the owner | Visible to everyone in the household. |
| Invite codes | Who created each code, when it expires, and who used it. A code works for 7 days. |
| Chores | Name, description, category, schedule, and whose job it is. |
| What happened to each chore | Who did it, skipped it, snoozed it or reopened it, and when. This is the household's activity history, visible to its members. |
| Nudges and notifications | Who was sent what, by whom, when, and whether it was delivered. A nudge or a "done" notification contains the sender's name and the chore's name, for example "Sam did it." |

Please do not put sensitive information (for example health details) into chore names or
descriptions: the rest of your household can read them.

### 3.3 From your phone

| What | Notes |
|---|---|
| A push notification token | Only if you allow notifications. It lets us send notifications to that phone. |
| The phone's type (Android) | Sent with the push token. |
| Sign-in tokens | Kept in your phone's secure storage so you stay signed in. On our server we keep only a scrambled (hashed) copy of the long-lived token, never the token itself, with when it was created, last used and when it expires. |
| Your IP address | Seen by our server with every request and used, in memory only, to limit how often sign-in can be tried from one address. We do not store it in our database. Our hosting provider's web server logs each request, including the IP address, and keeps those logs for 3 days. |

The app does not collect your location, contacts, photos, files, or any advertising identifier,
and contains no analytics, crash reporting or advertising code.
The Android app does not ask for Android's advertising-ID permission: we remove it, and the related
ad-services permissions that Facebook's sign-in library would otherwise add, from the version we
publish.

### 3.4 If you pay for Plus

Plus is paid for through **Stripe**. You enter your card and billing details on Stripe's own page,
not in our app, and we never see or store them.

From Stripe we receive and keep, for the household you paid for: Stripe's identifiers for you as a
customer and for the subscription, the plan (annual or monthly), whether it renews, the date it is
paid until, its status (for example active or past due), and which member of the household pays.
We send Stripe our internal identifiers for your account and household, so that a payment is
credited to the right household. We do not send Stripe your name or email address; Stripe asks you
for what it needs on its page.

**How Stripe sells Plus to you.** Plus is sold through Stripe's Managed Payments service. The
"merchant of record" is **Sold through Link, LLC**, a Stripe company (Stripe is renaming its Link
service "Onelink"): your payment, receipt, invoice, tax and any refund or dispute are handled by it,
and your purchase appears as "sold through Link". For that purpose Stripe is a separate controller
of the payment details you give it, under its own privacy policy (https://stripe.com/gb/privacy)
and Onelink's (https://onelink.com/gb/privacy).

### 3.5 When you contact us

If you email us, we keep your email and our reply so that we can help you and keep a record of
what was asked and done.

## 4. Why we use it, and our lawful basis

| Purpose | Information used | Lawful basis under UK GDPR |
|---|---|---|
| Creating your account, signing you in and keeping you signed in | Sign-in information, tokens | Contract: we cannot provide the app without it |
| Running your household: chores, turns, the week chart, activity | Household and chore information, your name | Contract |
| Sending reminders, "done" and nudge notifications | Push token, notification content | Contract. You can turn notifications off in your phone's settings at any time |
| Plus: the trial, payments, renewals and what your household is entitled to | Payment information from Stripe | Contract |
| Keeping the service secure: limiting sign-in attempts, checking sign-in tokens, stopping stolen tokens being reused | IP address (in memory), hashed tokens, sign-in records | Legitimate interests: keeping accounts and the service safe |
| Keeping the household's history understandable after a member deletes their account (section 7) | The anonymised record of what that member did | Legitimate interests: the remaining members' interest in an accurate history of their own household. |
| Answering your messages and requests | Your email and what you tell us | Legitimate interests, or legal obligation for a data protection request |
| Keeping records the law requires, and dealing with legal claims | Payment and account records | Legal obligation; legitimate interests |

We do not use your information for advertising, profiling or automated decisions that affect you,
and we do not sell it.

## 5. Who we share it with

We use the following companies to run the app. Each only gets what it needs.

| Who | What for | What they get | Where |
|---|---|---|---|
| **Microsoft** (Azure) | Hosting our server and database | Everything in section 3 that is kept on the server | UK (UK West region) |
| **Expo** (650 Industries, Inc.) | Delivering push notifications | Your push token and the notification's title and text (which can contain names and chore names) | USA |
| **Google** (Firebase Cloud Messaging) | Delivering push notifications to Android phones, as the next step after Expo | Your push token and the notification | USA and elsewhere |
| **Stripe** (and its Link service) | Payments for Plus (section 3.4) | Our identifiers for your account and household; anything you type on Stripe's page | USA, Ireland and elsewhere |
| **Google, Microsoft or Facebook (Meta)** | Signing you in, whichever you choose | The sign-in request. These companies are separate controllers of your account with them, under their own privacy policies | Their own locations |

Facebook's sign-in library runs inside the app. It is set not to collect the
advertising ID and not to record app events such as installs or launches. Nothing is sent to Meta
unless you choose to sign in with Facebook; then Meta receives the sign-in request under its own
privacy policy.

The other members of your household see your name, the chores and what you did. That is the point
of the app.

We may also disclose information if the law requires it, or to protect our rights or someone's
safety, and to a buyer if the business or app is ever sold (they would be bound by this policy).

## 6. International transfers

Our server and database are in the UK. Some of the companies in section 5 are in the USA or process
data there. For **Expo**, **Google** and **Stripe** we rely on the UK's adequacy regulations for the
USA (the "UK Extension" to the EU-US Data Privacy Framework), under which each is certified;
Stripe's and Google's terms add the UK's standard transfer clauses if that certification ever stops
applying. **Meta**
(for Facebook sign-in) relies on the UK's International Data Transfer Addendum in its terms. Where
one of these companies acts for us (Expo, Google, and Stripe for our own records), our contract with
it includes the data protection terms the law requires.

## 7. How long we keep it

| What | How long |
|---|---|
| Your account (name, email, sign-in records) | Until you delete your account. |
| Sign-in tokens | Each phone's session lasts up to 60 days from its last use, then stops working. Expired sessions are removed the next time you sign in, and all of them when you delete your account |
| Push tokens | Until you sign out on that phone, the phone stops accepting notifications, or you delete your account |
| Household, chores and activity history | For as long as the household has members. When the last member leaves, the household and everything in it is deleted 30 days later, or when a Plus period paid for it ends, if that is later. |
| Records of notifications and nudges sent | 90 days, then deleted automatically. The clear-out runs when the service next sends a notification, so a record can occasionally last a little longer |
| Payment records we keep (section 3.4) | 6 years after the last payment, as tax and accounting law requires, even if the household or your account is deleted sooner |
| Payment records Stripe keeps | Under Stripe's own retention policy, which includes keeping records the law requires of it. We cannot delete these |
| Emails to us | 2 years after the matter is closed |
| Database backups | Our hosting keeps automatic backups for 7 days. Deleted information disappears from backups when they expire. |

### When you delete your account

Deleting your account (in the app, or by asking us: see section 8) does this straight away:

- Removes you from your household. Chores that were always yours become anyone's.
- Deletes your sign-in records (your provider, your identifier with it and the email address it
  gave), your push tokens and all your sessions, which signs you out everywhere.
- Deletes our records of the notifications sent to you and the nudges and notifications sent by
  you. In our records of notifications sent to other members of any household you were in, your
  name is replaced with "Deleted user".
- Erases your name, email address and profile picture link from your account record, which then
  shows as "Deleted user".
- If you pay for Plus for a household, tells Stripe to stop the subscription at the end of the
  period already paid for. The household keeps Plus until then. Nothing is refunded automatically.

What is kept, and why:

- **An anonymous account record**, with no name or email address, so that the household's history
  still makes sense to the people left in it ("Deleted user did the bins"). It holds only an
  internal number and the dates the account was created, last used and deleted.
- **The household's own information**: its name, its chores and its activity history, which belong
  to the household and stay for its other members. If you were the last member, the household
  stays on the server as described in the table above.
- **Records of notifications sent to other members**, with your name replaced by "Deleted user",
  until they are deleted after 90 days like all notification records. Notifications already
  delivered to other members' phones stay on those phones; we cannot reach them.
- **What Stripe keeps** about a payment, under its own policy.
- **Anything in our backups**, until the backups expire (above).

## 8. Your rights

Under UK data protection law you have the right to:

- **access** the personal information we hold about you and get a copy;
- have it **corrected** if it is wrong;
- have it **erased** (you can also do this yourself in the app);
- **restrict** how we use it, or **object** to our using it where we rely on legitimate interests;
- receive it in a portable format, or have it sent to someone else, where we rely on contract;
- complain to the regulator (below).

To use any of these rights, email **support@altiora-technology.co.uk** from the email address you
sign in with, if you can. We may ask you for information to confirm the account is yours before we
act. We will reply within one month. There is no charge.

**Deleting your account without the app:** see our account deletion page at
https://notyourturn.azurewebsites.net/delete-account.

## 9. Complaints

If you are unhappy with how we have used your information, please tell us first and we will try to
put it right. You can also complain to the Information Commissioner's Office:

- Website: https://ico.org.uk/make-a-complaint/
- Phone: 0303 123 1113
- Post: Information Commissioner's Office, Wycliffe House, Water Lane, Wilmslow, Cheshire SK9 5AF

## 10. Children

Not Your Turn is for people aged **18 and over**. You must be 18 or older to create an account.
We do not knowingly collect information from anyone younger. If you believe a child has created an
account, email us and we will delete it.

## 11. Security

All traffic between the app and our server is encrypted (HTTPS; the release app refuses
unencrypted connections). Your sign-in tokens are kept in your phone's secure storage, and the
server keeps only scrambled copies of long-lived tokens. Our database is hosted by Microsoft Azure
in the UK and only Altiora Technology can reach it. Card details never reach us. No system is
perfectly secure; if a breach puts your information at risk we will tell you and the ICO as the
law requires.

## 12. Changes to this policy

We will update this page when what we collect or how we use it changes, and change the date at the
top. If a change is significant we will tell you in the app before it takes effect.

## 13. Contact

Tim Cooley, trading as Altiora Technology, 19 The Sidings, Bishops Itchington, Southam, CV47 2EJ
Email: support@altiora-technology.co.uk

Related pages: [Terms of Use](terms.md) · [Delete your account](delete-account.md)
