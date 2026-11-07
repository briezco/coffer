# Coffer

An envelope-budgeting app for Windows. Give every dollar a line, record
what you spend against it, and see where your habits actually are.

It is a **ledger, not a forecast** — built for recording what already
happened, keeping it against a plan when real life forces a deviation
from it, and answering whether you can afford the thing you want yet.

## Download

**[Download Coffer for Windows](https://github.com/briezco/coffer/releases/latest)**
· Windows 10 or 11, 64-bit.

Windows will warn you about it. The installer is not signed by a
certificate authority — that costs a few hundred dollars a year — so
SmartScreen shows a blue dialog saying it protected your PC. Click
**More info**, then **Run anyway**. The alternative is a signing
certificate, which proves somebody paid for one and nothing else.

Coffer updates itself after that: it checks on launch and offers the
new version, and only installs what matches the hash published here.

## Your data

Your budget is a single file on your own machine, under
`%APPDATA%\io.github.brieco\coffer`. There is no account, no server, and
nothing to sign up for. Nobody else has a copy, including me — so keep
your own: **Menu → Export** writes the whole budget to spreadsheets you
can put anywhere, and **Import** reads them back.

## What it does

- **Lines.** Envelopes. Income is allocated across them, spending comes
  out of them, and each one carries its own balance and history.
- **A plan, applied.** Set what each line should get and what the
  recurring bills are, then apply it to a month. The plan and what
  actually happened stay separate.
- **A ledger.** Every entry, filterable, with one expense divisible
  across several lines.
- **Money owed to you.** Cover dinner for a table of people and each
  debt is tracked separately, out of your budget until it comes back.
- **Estimates.** Record a payment at the figure on the receipt and flag
  it, for when the card posts a different number two days later.
- **Habits.** Where the money went, by category, payee and day, against
  the months before it.
- **A wishlist**, which can hold money of its own, and will tell you
  when you can afford something at the rate you are saving.

Nothing leaves the app. There are no ads, no subscription and no
upsell in it.

## Status and support

Version 0.5.0 — working, in daily use by its author, and still having
its wording revised. If something is wrong, open an issue here and say
what you were doing when it happened.

Android and iOS are not built yet.
