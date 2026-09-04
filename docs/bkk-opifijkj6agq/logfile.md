# qa38-client, Wanjiru Kamande, nail shop price list

<!-- ledger:status -->
status: in_progress
now: One page price list built and handed back to Wanjiru for her real prices.
blockers: Wanjiru did not send her actual services and prices, so the page ships with clearly marked sample prices.
next: Wanjiru confirms real prices and shop details, then remove the sample notice and publish.
updated: 2026-09-04 19:50
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
