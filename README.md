# Shahed Salong – website draft

Demo one-page website for Shahed Salong, Västra Storgatan 59, Kristianstad. Swedish, English and Arabic (RTL). Single static `index.html`, no build step.

**Status: DRAFT / DEMO.** The page shows a "DEMO · Förslag till ny webbplats" banner and is set to `noindex, nofollow`. It is not an official site of the salon.

## Before going live (checklist)
1. Get the owner's approval.
2. Confirm opening hours (currently copied from the salon's Google Maps listing: Mon–Sat 10:30–23:00, Sun 11:30–20:00).
3. Get a real price list and add it; remove the "Ring eller skriv för pris" placeholders.
4. Confirm the services offered (haircuts for women and men; colour and styling copy is general).
5. Replace all hotlinked Google Maps photos with the salon's own photos (with permission). Google image URLs can expire.
6. Remove the draft banner (`.draft-note`) and the `<meta name="robots" content="noindex, nofollow">` tag.
7. Reviews are shown anonymously as "Google-recension". Keep names out unless the reviewers agree.

## Contact links
Phone, WhatsApp and SMS all use `+46760099771`. Search and replace that value, and the visible `076-009 97 71`, if the number changes.

## Deploy
GitHub Pages: **Settings → Pages → Deploy from a branch → main / (root)**. Any static host also works.
