# Privacy Policy — SpunkyChicken

*SpunkyChicken · Secure Contact Card*

SpunkyChicken provides Secure Contact Card: a contact card issued to you by your organization,
delivered by text message and kept on your phone or tablet. There are no accounts, no sign-up and
no advertising. This policy explains what is collected, why, and who handles it.

**Last updated: October 21, 2026**

[Privacy policy](privacy.md) · [SMS terms](terms.md)

## At a glance

- **Never sold or shared for marketing.** Your mobile number and your consent to receive texts are
  not shared with third parties or affiliates for marketing or promotional purposes.
- **Service texts only.** Card links, device checks and set-up codes. No marketing messages.
- **Frequency and cost.** Message frequency varies, typically fewer than five a month. Message and
  data rates may apply.
- **Opt out any time.** Reply `STOP` to any text to stop. Reply `HELP` for help.

## Contents

- [Text messages](#text-messages)
- [Apple Wallet card (iPhone)](#apple-wallet-card-iphone)
- [Apple Push Notification service](#apple-push-notification-service)
- [iPad app](#ipad-app)
- [Android app](#android-app)
- [What the service records](#what-the-service-records)
- [Sharing](#sharing)
- [Security](#security)
- [Your choices](#your-choices)
- [Children](#children)
- [Changes to this policy](#changes-to-this-policy)
- [Contact](#contact)

## Text messages

SpunkyChicken sends text messages (SMS and MMS) about your card, on behalf of the organization that
issued it. The [SpunkyChicken SMS terms](terms.md) cover the program in full.

### What we collect

Your mobile phone number, and a record that you agreed to receive SpunkyChicken text messages at
that number. Nothing else about you is collected for the text message program.

### How you opt in

You give your mobile number to the organization issuing your card, or to SpunkyChicken, and agree
to receive SpunkyChicken text messages about your card at that number. Messages are sent only after
you agree. Agreeing is not a condition of any purchase.

### How we use your number

Only to send the service messages you agreed to:

- a link to add your card, or an update to it;
- a request to confirm that your device is still with you;
- a set-up code, sent as a picture message, for adding your card to a tablet.

We do not send marketing or promotional messages. Message frequency varies, typically fewer than
five a month. Message and data rates may apply.

### Opting out

Reply `STOP` to any message to stop receiving them. You will get one message confirming it, and
nothing after that. Reply `HELP` for help.

### Who carries the messages

Messages are carried by our messaging provider, Twilio, solely to deliver them. Twilio receives
your number and the content of each message for that purpose. Each message's record, including its
text and any picture, is deleted from Twilio once it has been delivered or has failed.

## Apple Wallet card (iPhone)

On iPhone your card is an Apple Wallet pass. There is no app to install. The pass is signed by the
organization that issued it, and Apple Wallet keeps it on your iPhone, protected by your iPhone's
passcode, Face ID or Touch ID. If your Wallet passes sync through iCloud, Apple keeps the pass on
your other devices signed in to the same Apple Account, under Apple's own privacy policy.

### What Wallet sends

When you add the pass, Wallet registers it with the card service run for the organization that
issued your card, so the card can be kept up to date. Wallet sends:

- an identifier Wallet makes up for your device, and a push token from Apple Push Notification
  service;
- the card's serial number and its update credential, when it asks for an update;
- Wallet's own error messages about the pass, if something goes wrong fetching it.

The service also keeps the time and country of the card's first device registration with the
card's record, so that a card used on more devices than it was issued to can be noticed.

### Removing the pass

Removing the pass from Wallet deletes it from your iPhone and tells the service to stop sending
updates to that device.

## Apple Push Notification service

Updates reach Apple devices through Apple Push Notification service (APNs), not by text message.
APNs receives a push token that identifies the device, so it can route the push. Apple handles that
token under Apple's own privacy policy.

- **Wallet pass.** The push carries nothing: no card contents, no name, no notice. It only tells
  Wallet to fetch the new card from the service over HTTPS. Wallet may then show the short headline
  of a notice from your organization on your lock screen.
- **iPad app.** When your organization posts a notice, the push carries that notice's short
  headline, signed by the organization. The app checks the signature before it shows anything.

That headline is the only part of your card's content that passes through Apple. Your numbers, your
login and the full notice never do.

## iPad app

An iPad cannot hold a Wallet pass, so on iPad your card is held in the Secure Contact Card app. The
app keeps your card encrypted with a key in the iPad's Secure Enclave. It opens only with Face ID,
Touch ID or your passcode, and it cannot be copied off the iPad or read while the iPad is locked.

The app sends an APNs push token and its update credential to the card service, and nothing else.

## Android app

### What the app stores on your device

- The contact card you were issued, encrypted. It is unlocked with your fingerprint, face or device
  PIN, and cannot be read without one.
- A login value, encrypted separately, shown only after you confirm again.
- A credential that lets the app ask for updates to your card. This one is not behind your
  fingerprint, because the app has to use it when an update arrives and you are not there. It is
  unreadable while your phone is locked.

All three are encrypted with keys held in your phone's secure hardware. They cannot be copied off
the device, and none of them can be read while the screen is locked. The app needs a screen lock to
work; without one it says so rather than store your card.

### What the app sends

- A notification token from Google Firebase Cloud Messaging, so your card can be told when it
  changes.
- The update credential above, when it asks for an update.

Both go only to the card service, over HTTPS. When your organization posts a notice, its short
headline is delivered through Firebase Cloud Messaging so your phone can show it without being
unlocked. Nothing else about your card is sent to Google.

## What the service records

When a phone, tablet or Wallet asks for an update, the service notes the address it connected from,
along with what was asked for and when. Those records are deleted after ninety days.

They exist so that a card used on more devices than it was issued to can be noticed. They are not
used to work out where you are, they are not combined with anything else, and they go nowhere else.

## Sharing

We do not sell your information, and we do not track you, profile you or show advertising. The app
does not collect your name, email address, phone number or contacts. Your phone number is held only
for the text message program, never by the app.

Information is handled only by the service providers below, and only to deliver what this policy
describes:

- **Twilio**: delivers text and picture messages.
- **Apple**: Apple Wallet, iCloud sync of Wallet passes, and Apple Push Notification service.
- **Google**: Firebase Cloud Messaging on Android.

> No mobile information will be shared with third parties or affiliates for marketing or
> promotional purposes. Information sharing to subcontractors in support services, such as customer
> service, is permitted. All the above categories exclude text messaging originator opt-in data and
> consent; this information will not be shared with any third parties.

## Security

Your card is encrypted on your device with keys held in its secure hardware, and every request
between your device and the card service uses HTTPS. Wallet passes are signed, so a pass that has
been altered will not be accepted.

## Your choices

- **Stop text messages:** reply `STOP` to any SpunkyChicken text message.
- **Remove the card from a device:** uninstall the app, or remove the pass from Wallet. Either
  removes everything stored on that device and stops its updates.
- **Withdraw the card or remove your number:** contact the organization that issued your card, or
  reply `HELP` to any SpunkyChicken text message.

## Children

Secure Contact Card and SpunkyChicken text messages are not directed to children under 13, and we
do not knowingly collect information from them.

## Changes to this policy

If this policy changes, this page is updated and the date at the top changes with it.

## Contact

Secure Contact Card and its text message program are provided by SpunkyChicken. For questions about
this policy, reply `HELP` to any SpunkyChicken text message, or contact the organization that issued
your card.

---

© 2026 SpunkyChicken
