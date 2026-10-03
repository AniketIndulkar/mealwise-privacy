---
layout: default
---

# Privacy Policy for MealWise

**Last updated: 3 October 2026**

MealWise (`ai.novanest.mealwise`) is a meal, calorie and macro tracking app developed and maintained
by Aniket Indulkar (NovaNest). This policy explains what information MealWise handles, where it
goes, and the choices you have.

**In short:** MealWise has no account, no advertising and no analytics or tracking SDKs. Your meals,
photos, weight and notes are stored only on your device. The developer cannot see them. A few
features make limited network requests, listed in full under
[Information leaving your device](#information-leaving-your-device).

## Information stored on your device

MealWise keeps the following in its private app storage. It is created by you and never uploaded to
the developer.

- **Meals:** meal name, meal type, ingredients, date and time, portion size, calories, protein,
  carbohydrates and fat, tags, and how the meal was logged (typed, spoken, barcode or manual).
- **Meal photos:** pictures you take or choose for a meal. MealWise saves a smaller copy in its
  private storage.
- **How you felt:** an optional feeling and note you attach to a meal, used for the insights shown
  in the app.
- **Body and goals:** weight entries, calorie and macro targets, and your goal setting.
- **Templates and history:** saved meal templates and the frequency of foods you log, used for
  suggestions.
- **Settings:** theme, feature switches, reminder times and similar choices.
- **Food model file (optional):** if you download the on-device food model, the file is stored in
  MealWise's private storage.

This information is used only to provide the features you see in MealWise: your log, targets,
progress, insights, suggestions, reminders and home-screen widget. It is protected by Android's
application sandbox and is not made available to other apps by MealWise.

Weight, meals and how you feel can be considered health-related information. MealWise treats all of
it as private and does not send it anywhere.

## What MealWise does not do

MealWise has no sign-in. It does not show ads. It does not contain advertising, analytics or
behavioural-tracking SDKs. It does not access your contacts, location, files, accounts or
advertising identifier. It does not sell your information or share it for advertising.

## Information leaving your device

MealWise keeps your log on the device. The only network activity is the following.

### 1. Barcode lookup (Open Food Facts)

When you scan a barcode, MealWise sends the barcode digits to
[Open Food Facts](https://world.openfoodfacts.org/) (`world.openfoodfacts.org`) to fetch the
product's name and nutrition. Only digits that look like a product barcode are sent. No meal, photo,
account or personal information is attached. The request includes the app name, app version and the
developer's support address in the standard `User-Agent` header, which Open Food Facts requires.
Like any internet request, it reveals your IP address to Open Food Facts. Their handling is
described in the [Open Food Facts privacy policy](https://world.openfoodfacts.org/privacy).

### 2. Optional food model download

If you choose to download the on-device food model in **Settings**, MealWise downloads one file
(about 379 MB) over HTTPS from the server the developer configured for that purpose. The request
asks for the file only and carries no meal or personal information. The server can see your IP
address, as with any download. After the download, the model runs entirely on your device and your
typed and spoken meals are not sent to any server for understanding.

### 3. Crash and error reports (Sentry)

MealWise can send crash and error reports to [Sentry](https://sentry.io/) (Sentry's
[privacy policy](https://sentry.io/privacy/)). This is for fixing bugs only. When reporting is
enabled in the version you installed, a report can include:

- the error type and technical stack trace;
- the app version and build, Android version, and device details such as model and architecture;
- timing data for a sample of app operations, to find slow screens;
- a randomly generated installation identifier that is not linked to your identity or account; and
- your IP address, as part of the network request.

Reports are configured not to include personal information. They do not include your meals, meal
names, notes, photos, weight, targets or the text you type or speak. The developer uses reports only
to investigate and fix problems, and does not use them for advertising or profiling.

### 4. Voice logging (Android speech recognizer)

When you tap the microphone, MealWise asks Android's built-in speech recognition service to turn
your voice into text. That service is provided by your device and usually by Google, not by
MealWise. Depending on your device and settings, the recognizer may process audio on the device or
send it to its provider's servers, under that provider's privacy policy (for Google, the
[Google Privacy Policy](https://policies.google.com/privacy)). MealWise receives only the resulting
text. It does not record, keep or upload your audio. Voice logging is optional; you can type or scan
instead.

### Things that do not leave your device

- **Barcode scanning:** the camera image is analysed on your device. Only the barcode digits are
  used, as described above.
- **Meal photos:** stay in MealWise's private storage.
- **Reminders:** meal reminders are scheduled locally on your device. MealWise uses no push-notification
  service.
- **Home-screen widget:** it shows today's calories, macros and recent entries on your home screen.
  Anyone who can see your home screen can see it. You can remove the widget at any time.
- **Android backup and device transfer:** MealWise excludes its data from Android cloud backup and
  device-to-device transfer. If you uninstall MealWise or move to a new phone, your log does not come
  with you.

## Permissions

| Permission | Purpose |
|---|---|
| Camera | Scan product barcodes and take meal photos. Requested when you first use either. |
| Microphone | Voice meal logging, through Android's speech recognizer. Requested when you first tap the microphone. |
| Notifications | Show meal reminders. Optional. |
| Run at startup | Set your meal reminders again after the device restarts. Does nothing if reminders are off. |
| Internet | Barcode lookup, the optional food model download, and crash reports. The rest of the app works without it. |

You can change or withdraw any permission in Android Settings. MealWise keeps working without
camera, microphone or notification access, with the matching feature unavailable.

## Retention and deletion

Your information stays on your device until you remove it.

- **Delete a meal:** delete it in the app. Its photo copy is removed from MealWise's storage as well.
- **Delete everything:** in Android go to **Settings → Apps → MealWise → Storage → Clear storage**,
  or uninstall MealWise. This permanently removes your meals, photos, weight entries, targets,
  templates, settings and the downloaded food model.
- **Crash reports:** these are kept by Sentry for a limited period and are not tied to your name or
  account. To ask about reports from your device, contact the developer below; because reports are
  anonymous, the installation identifier or a description of the crash may be needed to find them.

The developer holds no server-side copy of your log, so there is nothing for the developer to
retrieve or delete from a server.

## Security

Your data is protected by Android's application sandbox, and all network requests made by MealWise
use HTTPS. MealWise does not add its own encryption to the on-device log. Protect it by using a screen
lock on your device.

## Children

MealWise is a general nutrition tool and is not directed to children under 13. It does not knowingly
collect personal information from anyone. If you believe a child has sent information to the
developer, contact the developer below.

## Your rights

Because your log lives only on your device, you already control it: view, change or delete it in the
app, or clear it from Android Settings. If you live where data protection law such as the GDPR or the
CCPA applies, you may also ask the developer what information it holds about you, or to delete it.
The developer holds none beyond any anonymous crash reports described above. Contact details are
below.

## Third-party services

| Service | Used for | Policy |
|---|---|---|
| Open Food Facts | Barcode product lookup | [Privacy policy](https://world.openfoodfacts.org/privacy) |
| Sentry | Crash and error reports | [Privacy policy](https://sentry.io/privacy/) |
| Android speech recognition (usually Google) | Voice logging | [Google Privacy Policy](https://policies.google.com/privacy) |

Nutrition data in the built-in food database is based on USDA FoodData Central. Product data from
barcode lookups comes from Open Food Facts contributors.

## Medical disclaimer

MealWise is a general wellbeing tool. It is not a medical device and does not give medical advice.
Talk to a doctor or registered dietitian before you change your diet.

## Changes to this policy

If MealWise's data practices change, this policy will be updated before a version with those changes
is released. The date at the top shows the latest revision.

## Contact

For privacy questions, email
[support@novanest.ai](mailto:support@novanest.ai) or open an enquiry at
[github.com/AniketIndulkar/mealwise-privacy/issues/new](https://github.com/AniketIndulkar/mealwise-privacy/issues/new).
GitHub issues are public, so do not include personal or sensitive information there.
