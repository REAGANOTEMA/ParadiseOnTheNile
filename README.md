# Paradise on the Nile Hotel, Coming Soon Page

Temporary launch page for **Paradise on the Nile Hotel, Jinja, Uganda**.
Built by **ReaganSoft Innovation Limited, Uganda**.
Enquiries: WhatsApp **+256 772 514 889**.

## Files
- `index.html` — single-page site (HTML + CSS + JS). No build step, no dependencies.
  Works by double-clicking the file or on any static host.
- `images/hotel.webp` — hero photograph of Paradise on the Nile Hotel used in the
  "Sanctuary Window" feature (replace it with an updated photo anytime).
- `images/meeting room.webp` — additional hotel photo (currently unused on the page;
  safe to use later or delete).
- `images/reagansoftinnovation-logo.jpeg` — ReaganSoft Innovation Limited logo used in
  the header badge and footer credit.

## Launch plan
- The website goes live (countdown) on **Friday, 9 October 2026 at 12:00 PM (noon)
  Kampala time (UTC+3)**.
- After the site is up, the full system and mobile apps take about **22 weeks** to
  complete, and will then appear on the **Apple App Store** and **Google Play**
  (estimated around March 2027).

## Launch date
- Automatic countdown to **Friday, 9 October 2026 at 12:00 PM (noon) Kampala time (UTC+3)**.
- The target is stored as an absolute timestamp `2026-10-09T09:00:00Z`, so it is correct in
  every visitor's timezone.

### To change the launch date
Open `index.html` and edit this single line:

```js
var TARGET_ISO = "2026-10-09T09:00:00Z";
```

Use an instant on the UTC clock (Kampala is UTC+3, so 12:00 PM Kampala = `09:00Z`).

### Notes
- The countdown re-reads the wall clock on every tick (every 250 ms), so it never drifts
  or desyncs, and never goes negative. After the target passes it switches to a "We're live!"
  state.
- The only social call-to-action is **WhatsApp** (`wa.me/256772514889`) with a prefilled
  message. The same number serves both hotel enquiries and developer contact
  (ReaganSoft), and the developer credit in the header and footer also links to it.
- Google Fonts (Cormorant Garamond + Jost) load from the web but gracefully degrade to
  system fonts if offline.
- Accessible: `role="timer"`, `aria-live`, skip-link, semantic landmarks, reduced-motion support.

## Deploy
Upload `index.html` to any static hosting (Netlify, Vercel, GitHub Pages, cPanel, hosting
control panel, or even a flash drive — it works from `file://` too).

## Phone / WhatsApp
+256 772 514 889 (Ursula-ReaganSoft line)