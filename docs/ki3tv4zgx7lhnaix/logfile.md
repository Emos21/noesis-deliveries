<!-- ledger:status -->
status: done
now: built Mumbi's car wash price page
blockers: empty
next: get Mumbi's real prices, business name, phone number, hours and location, then replace the placeholders and publish a link
updated: 2026-09-04 16:58
<!-- /ledger:status -->

## Log

### 2026-09-04
Mumbi, who runs a car wash in Kikuyu, asked for a small page with her wash
prices. Built index.html, a single self-contained file with no dependencies, no
JavaScript and no internet needed. Car wash pricing is two dimensional, so the
page is priced by service and by vehicle size: three tables (Washes, Deep clean
and finishing, One price any vehicle) across saloon, SUV and wagon, and van and
pickup, plus a legend explaining what each vehicle class means in local terms, a
Good to know panel and a footer with name, location, hours and contact. Light
theme, water blue accent, mobile first: under 600px each table row collapses into
its own card using data-label attributes, so nothing scrolls sideways on a phone.
Print styles added so she can pin the list up at the wash. No emojis, no em
dashes.

She gave us no figures at all, so every price is a clearly labelled placeholder
pitched at Kikuyu rates (body wash 250 to 450, full wash 600 to 900, full valet
3,500 to 5,000), the business name "Mumbi Car Wash" is a guess, and the phone is
0700 000 000 following the house convention for unknown numbers. A comment block
at the top of index.html lists the five things she must correct and shows how to
edit a price by hand; README.md repeats it in plain language for a non-technical
reader and offers to collapse to a single price column if she does not charge by
vehicle size.

Verified by reading the file back: tags balance, thead and tbody close, every
data row carries exactly three price cells with matching data-label values, and a
search for non-ASCII characters across all three files returned nothing, which
rules out emojis, em dashes and smart quotes. Could not run python3 or git for
verification, both are blocked for workers in this environment, so the check was
done by reading rather than by script; a temporary _verify.py was written for
that purpose and removed again. Nothing published: the page is local only until
Mumbi confirms her real prices.
