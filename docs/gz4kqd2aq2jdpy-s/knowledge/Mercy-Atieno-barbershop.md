# Mercy Atieno, barbershop in Kawangware

Client of Amerissa Studio, environment `amerissa/qa72-shop`.

## What she asked for (2026-09-08)

One simple page with her prices that she can show clients on her phone.
Three services named: haircut, shave, dye.

## What was built

`workspace/prices.html`, a single self contained page. Mobile first, light
theme, works offline, prints on A4.

## Open question, deliberately not guessed

She did not say what her prices are, and a made up number on a page she shows
paying clients is worse than a blank. The page therefore ships with the three
rows reading "Not set yet" and a one time note telling her to tap "Edit prices"
and enter her own. She sets them herself in about half a minute, and can change
them later without asking anyone. Prices are kept in the phone's own storage
and mirrored into the URL fragment so a shared link carries them.

If someone would rather ship the page pre filled, ask Mercy for her three
prices first. Do not fill them in from typical Kawangware rates.

## Not done here

- Nothing was published or sent. The page is a file in this workspace waiting
  on a handover step.
- No shop name, phone number or opening hours were given, so the page defaults
  to "Barbershop" with "Kawangware, Nairobi" above it, both editable.
- Tests were written but could not be executed in the worker sandbox, which
  refuses to run python without an approval. Verified by reading instead.

## Warning: another client's files are in this workspace

`workspace/index.html`, `workspace/prices-for-whatsapp.txt` and
`workspace/README.md` were written here by another worker mid task and belong
to Grace's shoe stall in Gikomba. They were left in place rather than deleted.
Mercy's own instructions are `workspace/prices-README.md`. Her deliverable is
`workspace/prices.html` and nothing of hers was lost.
