# Sparsh & Komal — Wedding Invitation 💛

A mobile-first, scroll-animated wedding invitation website.

**Flow:** scrapbook intro (groom → bride → meet the couple) → "Are you excited?" (YES / NO → *"Are you kidding me, bro?!"*) → confetti → scrolling invitation (Wait is Over, Save the Date, scratch-to-reveal date, invitation card, countdown, festivities, venue, our moments, WhatsApp RSVP, thank you).

## Edit the details
Open `index.html` and find the `CONFIG` block near the bottom (search for `EDIT YOUR DETAILS HERE`). Change:
- names, intro taglines, parents' names
- `weddingDate` (used for the scratch date, countdown and calendar link)
- events (name, date/time, place)
- venue name, address and Google Maps link
- `contact` and `mapsUrl` for the venue
- `showRsvp` — set to `true` (and fill `whatsapp`) to turn on the WhatsApp RSVP form

## Add music
Drop `intro.mp3` and `main.mp3` into the `music/` folder (see `music/README.md`).

## Put it online (free) with GitHub Pages
1. Repo → **Settings → Pages**
2. Source: **Deploy from a branch**, Branch: **main**, folder **/ (root)** → Save
3. After a minute the site is live at `https://vighyatojha.github.io/Sparsh-And-Komal-Wedding/`

Tip: add `#invite` to the end of the link to skip the intro and jump straight to the invitation.

Built with GSAP + ScrollTrigger and canvas-confetti (loaded from CDN).
