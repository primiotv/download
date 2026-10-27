# Primio · Tester notes

### Welcome to the Primio test

Primio is a player for TV, films and series. Primio does not provide any content: you bring your own source (an M3U
list or the Xtream login from your provider).

**Duration:** The test version runs for a limited time. Primio lets you know in good time; after that, Primio only shows
where to get the new version and no longer plays anything. Your sources, favourites and settings are kept — simply
install the new version over the old one (see "New version").

### Installing

1. Install the **Downloader** app on your TV.
2. **Fire TV:** first allow Downloader to install apps — Settings → My Fire TV → Developer Options → Apps from Unknown
   Sources. If Developer Options are missing: Settings → My Fire TV → About, then press the first entry with the
   device name (Your TV) seven times; afterwards they are there. On Fire TV smart TVs, "My Fire TV" is called
   "Device & Software".
   **Google TV:** Settings → Apps → Security & restrictions → Unknown sources, then allow Downloader.
3. **Downloader app: code 9316224** — enter it. Or enter this address in Downloader:
   `https://github.com/primiotv/download/releases/latest/download/primio.apk`. Then install.

### New version

Install the new version **over the old one** (as above, with the same code 9316224) — do **not** uninstall first. That way your
sources, favourites and recordings are kept.

From this version on, Primio tells you about new versions itself. Choose “Update now” – your sources and settings are
kept. Where that isn’t possible, Primio shows the Downloader code 9316224.

The first time you update, Android asks whether Primio may install apps. If you allow it, Android may close Primio. Then open Primio again: the update window comes back by itself, at the latest after about a minute. Choose “Update now” again.

### Devices

**Only for TV devices with a remote control. Smartphones and tablets are not supported yet.**

Primio needs **Android TV / Google TV from Android 8.0** or **Fire TV from Fire OS 7**. Names as in Amazon's device
specifications (developer.amazon.com, as of 16 October):

- **Works:** Fire TV Stick (3rd Gen, 2020), Fire TV Stick Lite (2020), Fire TV Stick HD with Alexa Voice Remote (2024),
  Fire TV Stick 4K (2nd Gen, 2023), Fire TV Stick 4K Max (2021 and 2023), Fire TV Stick 4K Plus (2025), Fire TV Cube
  (2nd Gen, 2019, and 3rd Gen, 2022).
- **Does not work:** Fire TV Stick 4K (1st Gen, 2018), Fire TV Stick up to 2019 (1st and 2nd Gen, Basic Edition),
  Fire TV Cube (1st Gen, 2018) and the Fire TV boxes from 2014 to 2017 (Fire OS 5 or 6); also every device with
  **Vega OS**: Fire TV Stick 4K Select (2025), Fire TV Stick HD (2026) and Fire TV Stick 4K (3rd Gen, 2026).
- Note: the Fire TV Stick HD exists with Fire OS 7 (2024, works) and with Vega OS (2026, does not work).
- Your model and Fire OS version are under Settings → My Fire TV → About.

### Good to know

- **The first import loads everything.** After you add a source, Primio loads channels, films, series and the TV guide
  in full; the page shows the progress. Depending on your provider, this takes a few minutes.
- **Search finds the beginnings of words.** "Tat" finds "Tatort", "ort" does not.
- **Recordings are stored in the app's memory and are deleted when you uninstall.** So always install new versions
  over the old one (see "New version").
- **If your login allows only one connection at a time, do not switch channels during a recording.** Otherwise the
  recording may stop.
- **On some devices with Android 14, scheduled recordings only start reliably while Primio is open.**
- **The name, server, user or password of your source** can be changed under Settings → Sources → "Edit" → "Name and
  login". Primio checks the connection before saving.
- **On the "Name and login" page your password is shown in plain text. Please do not send photos of it.**
- Everything is operated with the remote: arrow keys, OK, Back. Holding OK opens a menu in many places.

### What to report and how

Report everything you notice — errors, stutters, waiting times, texts that do not fit, and what you are missing.

1. **What you did** (e.g. "Live TV, changed group, then channel up twice").
2. **What you expected** and **what happened**.
3. **The time**, roughly is enough.
4. **Device** (model) and **Primio version** (Settings → Expert → Diagnostics).
5. If possible the **diagnostics report**: Settings → "Expert" at the top → Diagnostics → "Export as text". Addresses,
   server names and login details are removed before the export. Even so, please send it only to the contact below,
   not into an open group.

Please do **not** send login details, list addresses or photos showing your login details.

Report to: info@primio.tv

### A question for you: menu at the top or on the left?

Primio shows the main menu (Home, Live TV, Guide, Catch-up, Movies, Series, Recordings) as a bar **at the top**. Other
apps have it **on the left**. Which do you prefer, and why?

### What is sent when Primio crashes

**On the first start Primio asks whether crash reports and usage statistics may be sent; both are optional and can be changed in the settings.**

On the first start Primio asks whether it may send a report if it crashes. If you allow it, only the error, the device
model and the Android and app versions go to a service in the EU (Sentry). Login details, server addresses and your IP
address are never sent. You can change this at any time under Settings → Diagnostic data. Without
your permission Primio sends nothing; crashes then only appear in the diagnostics report you export yourself.
