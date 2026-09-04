# qa38-client, Wanjiru Kamande, nail shop price list

<!-- ledger:status -->
status: in_progress
now: Customer facing WhatsApp announcement written to CUSTOMER-MESSAGE.md, in three versions, with the link left as a placeholder because the page is not online.
blockers: Still no real prices, shop name, hours or phone from Wanjiru, and no public URL, so neither the page nor the announcement can go to her customers yet.
next: Get her real prices and details, drop the sample notice, publish the page, then give her the live link to paste into version 1 of the customer message.
updated: 2026-09-04 20:14
<!-- /ledger:status -->

Client: Wanjiru Kamande, small nail shop in Kahawa, Nairobi.
Ask, in her words: a simple one page price list she can put online, just her
services and prices, nothing fancy.

## Log

### 2026-09-04

Built the page from an empty environment. Delivered two files:

- `index.html`, the whole price list. Single self-contained file, no build step,
  no JavaScript, no external fonts or images, so it opens offline and can be
  dropped on any host as one file. Light theme, warm paper background, editorial
  serif masthead, dotted leader lines between service and price, KSh prefixed
  automatically so she types only the number. Responsive: leaders drop to a
  space-between row layout below 420px, extra air above 768px. Print stylesheet
  included so she can put it on the shop wall without wasting ink. Prices carry
  tabular numerals so the column lines up.
- `README.md`, plain language instructions for a non technical reader: how to
  edit prices, how to add or remove a service, and three ways to get it online.

Content is four groups, 20 rows: Hands (9), Feet (4), Hands and feet together
(2), Extras and finishes (5), plus hours, phone and a note that unusually long
or damaged nails may cost more.

Scope note, important. She gave no prices, no shop name, no phone and no hours.
Rather than ship a page with invented numbers presented as hers, every unknown
is a marked placeholder: `CHANGE ME` comments sit above each editable block, and
a visible yellow notice at the top of the page states the prices are samples.
The notice is one line, marked `DELETE THIS LINE`, so removing it is trivial
once her real prices are in. Only the location, Kahawa, came from her directly.

Not published. Putting sample prices on the public internet under her shop's
name would misinform her customers, so the files are handed over and publishing
waits on her confirming the real numbers.

Verified by reading the files back: all tags balanced, 20 price rows each with
exactly one name, leader and price span, every CSS class used in the markup is
styled, no `<script>`, no `http` or `https` requests of any kind, no emoji and
no em dashes in either file. Colour contrast checked against the paper
background: body ink well past AA, the rose accent at about 6.8 to 1 and the
muted grey at about 5.7 to 1, both passing AA for normal text. Browser rendering
was not screenshotted, as no browser check was run in this environment.

### 2026-09-04, second round: "send it to me"

Wanjiru asked for the page to be sent to her. The send did NOT happen. This
session runs under an instruction that forbids sending, publishing, deploying or
spending, so there was no lawful way to put the files in her hands from here.
Rather than report a delivery that did not occur, the round did the part that can
be done without a channel and stopped at the line.

Done this round:

- Re-verified both files by reading them back rather than trusting the earlier
  entry. `index.html`: 20 price rows, every one matching the exact shape
  `i-name` + `i-dots` + `i-price`; block tags balanced (15 opens, 15 closes, the
  two extra apparent opens are the words `<body>` inside the editing comment);
  no `<script>`; no `http` or `https` reference of any kind, so it opens with no
  network; the only `href` values are the `tel:` link and nothing else. Every
  class used in the markup has a rule in the stylesheet. The whole environment
  is pure ASCII, so no emoji and no em dashes, confirmed by search rather than
  by eye.
- Wrote `MESSAGE-TO-SEND.md`: the covering message to go out with the two
  files, addressed to Wanjiru in plain language, stating that the prices are
  samples and listing the four things needed back from her (shop name, services
  and prices, hours, phone). It is written to her rather than to an internal
  reader, so it still reads correctly if it travels with the page.
- Changed nothing in `index.html` or `README.md`. They were correct and the ask
  was to send them, not to alter them.

Two things for whoever picks this up:

1. The prices, shop name, phone number and hours on the page are still invented
   placeholders. Sending the file to Wanjiru herself is safe, since the yellow
   notice says so plainly. Publishing it publicly under her shop's name is still
   the wrong move and remains blocked on her real numbers.
2. The staged `.delivery` folder in this environment holds a copy of this
   logfile alongside her two files, because the stager takes every changed
   Markdown file. This logfile is an internal record and should not travel to a
   client or onto a public page. That behaviour lives in the organization's own
   repository, which this session may not touch, so it is recorded here rather
   than fixed.

### 2026-09-04, third round: the message to her customers

Her words: "fine. then write the message for me, a short whatsapp text i can
copy paste to my customers announcing the price list. make it sweet". Note this
is a DIFFERENT audience from round two. `MESSAGE-TO-SEND.md` is written to
Wanjiru from the studio; this round is written as Wanjiru to her customers, so it
is a new file rather than an edit of that one.

Added `CUSTOMER-MESSAGE.md`. Three versions, each short enough for one WhatsApp
message, warm without being sugary, and in her voice rather than a studio voice:

1. For once the page is online, with `[PASTE YOUR LINK HERE]` as the only thing
   she has to fill in.
2. For sending today, with no link at all. It invites the customer to reply with
   the word list, or to read it on the shop wall, which is a real channel she has
   now. This exists because she has no URL yet and a message built around a link
   she cannot paste is useless to her.
3. A one line version for WhatsApp status or an Instagram bio.

Two truth notes sit at the top of the file, kept to a line each: there is no link
yet, and the prices on the page are still samples, so nothing should go to
customers until her real numbers are in. A third note asks her to cross off any
service she does not offer, because the services named in the message come from
the invented sample page rather than from her, and a customer announcement
naming acrylic when she does not do acrylic would cost her a walk in.

Also included a short practical note that a normal WhatsApp account throttles
mass identical sends, pointing her at a Broadcast list and roughly 100 people at
a time. She asked for a copy paste text, and a text that gets her account
limited would not have been the thing she asked for.

Nothing was sent. This session cannot send, publish or deploy, and the message is
for her to send from her own phone anyway, which is what she asked for.

Verified by reading the file back: pure ASCII confirmed by search, so no emoji
and no em dashes, matching house rules. Three link placeholders, all identical in
wording so a find and replace catches every one. The emoji question was left to
her explicitly, since it is her voice to her own customers, but none was written
in. Changed nothing in `index.html`, `README.md` or `MESSAGE-TO-SEND.md`.
