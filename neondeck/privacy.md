[Türkçe](gizlilik.md)

# NEONDECK Privacy Policy

_Last updated: 2026-11-12 (Firefox)_

NEONDECK is a browser extension for Firefox and Chrome that replaces the new tab page with a dashboard. This policy explains what happens to your data. In short: **NEONDECK has no servers, no accounts, no analytics and no ads. Your data stays in your browser.**

## What NEONDECK stores

Everything you set up is saved only on your device, in the browser's local extension storage (`storage.local`):

- settings (name, language, theme, display options, search engines)
- your netlinks (saved links and categories)
- widget content: notes, tasks, habits, world clock zones, AI quick links, Pomodoro timer state, the city you chose for weather
- a short-lived weather cache (refreshed every 15 minutes)

This data is not synced to other devices and is never sent to the developer. Uninstalling the extension, or using **Settings → Data → Reset to defaults**, deletes it.

## Network requests

NEONDECK itself contacts only one service, and only if you turn on the **Weather** widget and choose a city:

- **Open-Meteo** (`api.open-meteo.com`, `geocoding-api.open-meteo.com`) receives the city name you type when searching for a location, and the chosen location's coordinates rounded to two decimals (about 1 km). Requests are sent without cookies and without a referrer. See Open-Meteo's terms and privacy information at https://open-meteo.com/.

In Firefox, this is declared as optional *location* data: Firefox asks for your consent before the first weather request, and you can withdraw it at any time in the add-on's permissions. Without consent the widget sends nothing.

No other request is made by the extension. When you search or open a link, your browser simply navigates to that website (for example your chosen search engine); what that website does is covered by its own privacy policy.

## Optional permissions

NEONDECK installs with the `storage` permission only. Further permissions are optional and are requested only when you click the related button:

- **Site favicons (`favicon`, Chrome only)**: shows website icons from the browser's own icon cache. No request is made to the websites.
- **Browser bookmarks (`bookmarks`)**: read once, when you click **Import bookmarks**, to copy bookmarks into your netlinks on your device. Bookmarks are not sent anywhere.

You can revoke them at any time in **Settings → Permissions** or on the browser's extensions page.

## Backups

**Export JSON** creates a file on your computer; **Import JSON** reads a file you choose. These files never leave your device unless you share them yourself. Uploaded backgrounds are not included.

## What NEONDECK does not do

- no user accounts or sign-in
- no analytics, telemetry, tracking or advertising
- no sale or sharing of data with anyone
- no remote code: everything the extension runs is included in the package

## Children

NEONDECK does not knowingly collect data from anyone, including children.

## Changes

If this policy changes, the new version will be published at the same address with a new date.

## Contact

Questions: kurogrid.dev@gmail.com
