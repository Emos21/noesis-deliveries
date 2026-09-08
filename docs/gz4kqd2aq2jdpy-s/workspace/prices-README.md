# Your price page

For Mercy, barbershop in Kawangware. This file goes with `prices.html`.

Note: `README.md`, `index.html` and `prices-for-whatsapp.txt` in this folder
belong to a different client (a shoe stall in Gikomba) and landed here by
mistake. They are nothing to do with your page. Your page is `prices.html`
and these are its instructions.

The file `prices.html` is your price list. It is one single file, so it works
on your phone with no internet and nothing to install.

## Putting your prices in (do this once)

1. Open the page on your phone.
2. Tap **Edit prices** at the bottom.
3. Type your shop name, then your price for Haircut, Shave and Dye.
   Numbers only, for example 150.
4. You can also add your phone number or a short line like "Open 8am to 8pm".
   Leave it empty if you do not want one.
5. Tap **Save**.

The note at the top disappears once you save, and the page is then ready to
show clients.

## Everyday use

- Open the page and hand your phone to the client. That is all.
- The prices stay saved on that phone, so you do not redo this every time.
- When a price changes, tap **Edit prices**, change the number, tap **Save**.
- To send the page to someone else, share the whole link including the part
  after the `#`. Your prices travel with it.

## Good to know

- Nothing is sent anywhere. The prices sit on your own phone only.
- If your phone is in private browsing it cannot remember the prices, and the
  page will tell you so when you edit.
- It also prints tidily on A4 if you ever want one for the wall.

## For whoever maintains this

`test_prices.py` checks `prices.html`: the three services are present, it is
one self contained file with no outside requests, no prices are invented in
the shipped file, storage failures are caught, and the house style holds. Run
it with `python3 -m unittest discover -s . -p 'test_*.py'` from this
directory. It has not been executed yet: the worker sandbox that built the
page refuses to run python without an approval.
