# Wedding Reception Invitation — Fouzi & Ribinsha · Favaz & Shahma

## 1. Deploy
`npx vercel --prod` (or drag this folder into Vercel).

## 2. Social sharing preview (after deployment)
The source intentionally does not contain a fake `YOUR-SITE` URL. After deployment, add your real HTTPS site URL to `og:url`, `og:image` (use `/thumbnail.png`), and `twitter:image` in `index.html`, then redeploy. This is needed for reliable WhatsApp/social thumbnail previews. The included `thumbnail.png` is 1200 × 630 pixels.

## 3. Optional settings — `CONFIG` block near the bottom of `index.html`
- `whatsapp` — e.g. `"919XXXXXXXXX"` → shows the "Confirm on WhatsApp" button
- `phone` — e.g. `"+919XXXXXXXXX"` → shows the "Call Us" button
- `mapsLink` — paste the venue's Google Maps share link for an exact pin

## 4. Optional files
- `paper-turn.mp3` — page-turn sound played when the seal is tapped (included)
- `music.mp3` (and optionally `music2.mp3`, `music3.mp3`, `music4.mp3`) — your background nasheeds/songs, played in order and repeated. Add it next to `index.html`; it fades in right after the page-turn sound and a music button appears. Use a file you have the right to use.
- `thumbnail.png` — included (1200×630); replace to change the share preview

## Before sharing
- Confirm the venue address and exact Google Maps pin with the family. The page currently uses “Fathima Lounge, Salafi Road, Valanchery, Malappuram, Kerala”; do not rely on the directions until the pin is verified. Set `mapsLink` in the CONFIG block to the exact Google Maps share URL when available.
- Confirm names, date, and time with the family.

## Notes
- Page is set to `noindex` so search engines don't list a private invitation.
- All times are Indian Standard Time (IST, +05:30).
