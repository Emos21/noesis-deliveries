# Cherono Beauty price list

Faith, here is your one page price list. There are two versions of the same
list, because WhatsApp handles them differently. Use whichever suits the
moment, or both.

- `index.html` is the page. It opens on a phone or a computer, and it prints
  on one sheet of paper. Good for a link, a poster, or a screenshot.
- `whatsapp-message.txt` is the same list as plain text, ready to paste
  straight into a WhatsApp chat or your status. No link and no download
  needed, the customer just reads it in the chat.

## First, the important part

The prices in both files are examples. They are not your prices. We do not
know what you charge, so we put in the kind of numbers a salon your size in
Nakuru tends to charge, only so you can see the shape of the thing.

Change every number before you show this to a customer.

## Changing the page (index.html)

Open it in any text editor: Notepad, Text Editor, or the Files app on your
phone. Three things to change.

1. **The prices.** Look for lines like this:

   ```
   <li><span class="item">Manicure</span><span class="price">KSh 300</span></li>
   ```

   `Manicure` is the service. `KSh 300` is the price. Type over either one.
   Leave the pointy brackets exactly as they are.

2. **Your phone number.** Near the bottom, find `07XX XXX XXX` and put your
   real number there.

3. **The yellow bar.** At the top of the page there is a yellow reminder. In
   the file it sits between two lines that say `DELETE THIS BAR, FROM HERE`
   and `TO HERE`. Delete the bar and those two marker lines.

To remove a service, delete its whole `<li>...</li>` line. To add one, copy
any `<li>...</li>` line, paste it underneath, and change the words and the
price. If you do not offer a whole group, delete its heading line (for
example `<h2>Makeup</h2>`) and the list under it.

## Changing the message (whatsapp-message.txt)

Simpler. Open it, type over the numbers, put your real phone number in, and
follow the short note at the top of the file about what to copy.

## Getting it onto WhatsApp

Three ways, easiest first.

- **Paste the text.** Open `whatsapp-message.txt`, copy the message part, and
  paste it into the chat. Works for everyone, on any phone, right now.
- **Send a picture.** Open `index.html` on your phone and screenshot it, or
  open it on a computer, press Print and choose "Save as PDF". Send the
  picture or the PDF as an attachment. This is the one that looks smartest in
  a customer's chat.
- **Send a link.** Put the page online free, then paste the link. Go to
  app.netlify.com/drop and drag this whole folder onto the page. It gives you
  a link straight away, no account needed to start. That link works in your
  WhatsApp status, your Facebook page, or your TikTok bio.

You can also send `index.html` itself as a file on WhatsApp, but the customer
has to download it before it opens, so a picture or a link is better.

## If you want changes

Send the studio your real prices, or any services we missed or got wrong, and
we will update both files for you.
