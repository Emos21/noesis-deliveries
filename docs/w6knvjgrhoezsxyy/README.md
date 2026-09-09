# Njeri Tailoring, two one page documents

Two files, both finished and ready to use. Neither one needs the internet, so
they work even when your data bundle is finished.

| File | What it is for |
| --- | --- |
| `index.html` | The price list you show customers on your phone. |
| `opening-hours.html` | The card you print and stick on the door. |
| `njeri-opening-hours-card.pdf` | The fresh, print-ready A4 opening-hours card. |
| `njeri-opening-hours-card.html` | The editable version of the fresh card. |

## How to use the price list on your phone

1. Save `index.html` on the phone, or let us put it on a web link for you.
2. Open it. It fits a phone screen, and the customer can scroll it themselves.
3. Nothing to install, no app, no data needed once it is on the phone.

If you would rather send it on WhatsApp as a picture, open the page and take a
screenshot, or ask us and we will send you a picture version.

## How to print the door card

1. Open `njeri-opening-hours-card.pdf` on a computer or a phone.
2. Choose Print, A4, portrait, and actual size. Turn off headers and footers.
3. Stick the printed card on the door.

The card is designed to still read well if the shop printing it only has black
ink, so you do not need colour printing.

## Numbers you should check before you show anyone

We wrote the list so it is complete and usable today, but you know your shop
better than we do. These are the things worth a quick look, and any of them
can be changed in a minute:

- **The prices.** They are written as starting prices, for example "from 700".
  All of them sit in `index.html`. Each one is on its own line and the number
  is the last thing on that line, so it is easy to change.
- **The opening hours.** Right now the card says Monday to Friday 8:00am to
  6:30pm, Saturday 8:00am to 6:00pm, and closed on Sunday and public holidays.
  They are in `opening-hours.html`, one day per line.
- **The shop name.** Both files say "Njeri Tailoring". Change the words between
  `<h1>` and `</h1>` in each file if the sign outside says something else.
- **The four rules at the bottom of the price list**: half paid on order, the
  rest on collection, 3 to 5 days for normal work, and an extra 300 for urgent
  work. Change or remove any of them.

## Adding your phone number

We did not put a phone number on either page, because we did not want to print
a made up one on your door. Both files have a short note in them showing exactly
where to put yours. In `index.html` look for the line about
"TO ADD YOUR PHONE OR WHATSAPP NUMBER" near the bottom, and the same in
`opening-hours.html`. Or tell us the number and we will put it in for you.

## Checking the files still work

If anything is edited later, run this from this folder to confirm nothing broke:

```
python3 tests/check_pages.py
```

It checks both pages open cleanly, that the prices and the hours are all
present, and that no leftover editing marks were left behind.
