<!-- ledger:status -->
status: done
now: built Wanjiku's samosa price page
blockers: empty
next: get Wanjiku's real prices, phone number and M-Pesa answer, then replace the placeholders
updated: 2026-09-04 15:31
<!-- /ledger:status -->

## Log

### 2026-09-04
Wanjiku, who sells samosas outside the college, asked for a small page with her
prices. Built index.html, a single self-contained file with no dependencies:
three priced items (beef, chicken, vegetable samosa), a short Offers panel, a
Good to know panel and a footer with her name and contact. Light theme, warm
paper palette, mobile-first at 375 with a 768 breakpoint, plus print styles so
she can print a stall card. No emojis, no em dashes.

She did not tell us any actual figures, so every price is a clearly labelled
placeholder (Ksh 30 / 35 / 20), the phone number is 0700 000 000 following the
house convention for unknown numbers, and "Cash or M-Pesa" is a guess. A comment
block at the top of the file lists exactly what she must confirm and shows how to
edit a price by hand. Verified by reading the file back: tags balance, the
document is ASCII only, and the grep for emojis and em dashes came back empty.
Did not enroll a vault or Ledger symlink, since that lives outside this
environment.
