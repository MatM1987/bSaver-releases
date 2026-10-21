# bSaver Privacy Policy

**Effective date:** 21 October 2026

bSaver does not collect, store or share any personal data. Everything it reads about your Mac stays on your Mac. It connects to the internet only to check for updates and to verify your licence key.

## Who is responsible

bSaver is developed by Mateusz Matyszczuk ([bsaver.pl](https://bsaver.pl)). For any question about this policy or your data, contact **support@bsaver.pl**.

## What bSaver reads on your Mac

To limit charging, bSaver reads the following from macOS, **only on your Mac**:

- battery charge level, charging state, cycle count, capacity, health and power readings;
- whether a charger is connected and its power rating.

It saves only what it needs to work, all locally:

| What | Where | Purpose |
| --- | --- | --- |
| Your charge settings (limit, range, sleep option) | `/Library/Application Support/bSaver/` | Keep your settings between restarts |
| Event log (for example "charger off at 80%") | `/var/log/bsaver.log` and `~/Library/Logs/bSaver/` | Troubleshooting; capped in size and never sent anywhere |
| Your licence key, its type (Personal or House) and when it was last checked | Your Mac's keychain | Unlock bSaver after the free trial |
| When the free trial started | Your Mac's keychain and `/Library/Application Support/bSaver/` | Count the 7-day trial |

None of this leaves your Mac unless you choose to send it to us, for example by attaching a log to a support email.

## Internet connections

bSaver connects to the internet for **two purposes only**.

**1. Verifying your licence.** When you enter a licence key, and then about once a month, bSaver sends the key and bSaver's product identifier to Gumroad (`api.gumroad.com`), the store that sold you the licence, to check that it is valid and hasn't been refunded. Nothing else about you or your Mac is sent. Gumroad already has your purchase details from the sale, and processes the request under the [Gumroad Privacy Policy](https://gumroad.com/privacy). bSaver keeps only the key, the licence type and the dates in your keychain.

**2. Checking for updates.** Once a day, and when you choose **Check for Updates…**, it downloads a small update list from GitHub (`github.com`). If an update is available and you install it, it downloads the update from GitHub too.

- These requests contain only what any web request contains: your IP address and a technical identifier of the app and macOS version (the "user agent").
- bSaver does **not** send your battery data, settings, logs, or any information about you or your Mac's contents.
- Optional system-information reporting in the update component is **turned off**.
- GitHub processes these requests under the [GitHub Privacy Statement](https://docs.github.com/en/site-policy/privacy-policies/github-general-privacy-statement). We don't receive or see any data about who checks for updates.

You can turn off automatic update checks in the app.

## Reminders

After the free trial, bSaver may show an occasional notification on your Mac (daily at first, then weekly) as a reminder to buy a licence. These are created on your Mac; nothing is sent anywhere.

## What bSaver does not do

- No accounts or sign-in.
- No analytics, tracking, advertising or crash reporting.
- No selling or sharing of data with anyone.

## The background helper

bSaver installs a small helper that runs with administrator privileges, because macOS requires that to switch charging on and off. The helper only reads battery and power information and changes the charging setting. It does not access your files, network or other apps, and it only accepts instructions from the genuine, signed bSaver app.

## Support emails

If you email us, we receive your email address and whatever you write or attach. We use it only to answer you, and we don't add you to any mailing list. You can ask us to delete your emails at any time.

## Your rights

Because bSaver doesn't collect personal data, there is normally nothing for us to access, correct or delete. For support emails, you can ask for a copy or deletion at any time at support@bsaver.pl. If you are in the EU, you also have the right to complain to your local data protection authority (in Poland, the UODO).

## Removing your data

Uninstalling the helper (gear menu → **Uninstall Helper**) and deleting the app stops all activity. To also remove settings and logs, delete the folders listed above.

## Children

bSaver is a general-purpose utility and does not knowingly process any data from children.

## Changes to this policy

If this policy changes, the new version will be published at the same address with a new effective date, and noted in the release notes.

*17 October 2026: support address changed to support@bsaver.pl and website added.*
*21 October 2026: licence-key verification with Gumroad, trial dates and reminders added (bSaver 1.6.0).*
