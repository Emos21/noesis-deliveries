# Your price list, how to use it

The whole price list is one file: `price-list.html`. It works with no internet
once it is on your phone. Nothing to install, nothing to pay for.

## Put it on your phone

1. Send `price-list.html` to yourself on WhatsApp or email, then open it on the
   phone. It opens in Chrome.
2. In Chrome, tap the three dots at the top right, then "Add to Home screen".
3. Now it sits on your home screen like an app. One tap and the price list is
   on the screen, ready to turn towards a customer.

If it ever opens as text and code instead of a proper page, the file name lost
its ending. Rename it so it ends in `.html` again.

## Showing it to a customer

- Tap "Bigger text" once and the whole list gets larger. Good for customers who
  do not have their glasses. It stays big until you tap it again.
- Type in the search box to jump straight to one thing. One word works best:
  `battery`, `screen`, `charging`, `water`. Clear the box to see everything.
- The grey buttons under the search box jump to a section: Screens, Battery,
  Software, and so on.

## Changing a price

1. Open `price-list.html` on a computer with a plain text editor. On Windows use
   Notepad, on a phone use a text editor app, not Word.
2. Scroll down to the big block that says YOUR PRICES.
3. Every repair is one line, like this:

       ["Battery replacement, iPhone", "from 2,500", "ask by model"],

   The first part is what the customer reads. The second is the price. The third
   is the small grey note under the name, and you can leave it as empty quotes
   `""` if you do not want a note.

4. Change only the words between the quote marks. Leave the brackets, the quote
   marks and the comma at the end of the line exactly where they are.
5. Write `from 2,500` when the price changes by phone model, or just `2,500`
   when it is one fixed price. Write `Free` for anything free and it shows up in
   green.
6. To delete a repair, delete its whole line. To add one, copy a line, paste it
   underneath and change the words.
7. Save the file and open it again on the phone to check it.

If the page ever comes up blank after you edit it, you removed a bracket or a
comma by mistake. Undo your change and try again more slowly.

## Your shop name and number

Near the top of the file there is a line that says CHANGE THESE FOUR LINES.
Under it you can set your shop name, the line describing what you do, the area,
and your phone number. Change the number in both places on the phone line:

    <a id="shopPhoneLink" href="tel:+254700000000"><span id="shopPhone">0700 000 000</span></a>

The one after `tel:` is what dials when a customer taps it, the one after that
is what they read.

## Printing a copy for the wall

Open the file on a computer, press Ctrl and P together, and print. It prints in
two columns on one A4 page, without the search box, so it works as a poster
next to the counter.

## About the prices in it now

The prices in the file are typical Nairobi shop prices, put there so you have a
complete list from day one. They are a starting point, not your prices. Go
through them once and set your own before you show it to a customer.
