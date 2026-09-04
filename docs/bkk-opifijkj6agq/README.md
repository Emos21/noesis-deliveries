# Your price list page

Hi Wanjiru. This folder holds your one page price list. There is only one page
to worry about: **index.html**.

You can double click that file right now and it will open in your phone or
computer browser. Nothing needs to be installed, and it works without internet.

## First thing to do: put your real prices in

The prices on the page at the moment are **samples**. They are there so you can
see how it looks. They are almost certainly not your prices.

1. Open **index.html** with any text editor. On a phone, a notes or text editor
   app that can open files will do. On a computer, Notepad, TextEdit or Gedit
   is fine.
2. Look for the words **CHANGE ME**. Each one marks a spot to type over: your
   shop name, your area, your opening hours, your phone number, and each list
   of prices.
3. A price line looks like this:

   ```
   <li><span class="i-name">Plain manicure</span> <span class="i-dots"></span> <span class="i-price">300</span></li>
   ```

   Change `Plain manicure` to your service. Change `300` to your price. Leave
   everything else on the line exactly as it is.

4. To remove a service, delete the whole line from `<li>` to `</li>`.
   To add one, copy an existing line and change the words and the number.
5. When your real prices are in, delete the yellow notice box near the top.
   It is marked **DELETE THIS LINE**.
6. Save the file, then open it again in the browser to check it.

The word KSh is added automatically in front of every price, so you only type
the number.

## Putting it online

You do not need to buy anything to get this on the internet. Any of these work,
and they all just need the one file:

- **Easiest:** send **index.html** to whoever set up your Facebook or Instagram
  page, or to us, and ask for it to be put up. One file is all anybody needs.
- **Free hosting yourself:** open netlify.com/drop or pages.cloudflare.com in a
  browser, drag the file in, and it gives you a web address you can paste into
  your Instagram bio or WhatsApp status.
- **If you already have a website:** give this file to the person who runs it.
  It is an ordinary web page and will slot in.

We have not put it online for you, because that would mean publishing your
sample prices to the public. Once your real prices are in, say the word and it
can go up.

## Other things it can do

- **On a phone:** the page already fits small screens. The phone number is
  tappable, so a customer can call you straight from it.
- **Printing:** print the page and it comes out clean in black and white, with
  no background colour wasting your ink. Good for the wall in the shop.

## If something looks broken

You have probably deleted one of the `<` or `>` marks by accident. Undo your
last change, or ask us for a fresh copy of the file. Nothing you type can break
anything beyond this one page.
