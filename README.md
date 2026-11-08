# Coffer

Coffer is a (vibe-coded) envelope budgeting app and ledger for Windows. You can create 
a plan to determine how you want to allocate your money, record transactions against 
it, and view habits you develop over time. It's good for keeping track of your income,
spending, and saving up for those items on your wishlist!

## Download

**[Download Coffer for Windows](https://github.com/briezco/coffer/releases/latest)**

Supported platforms:
* Windows 10 or 11, 64-bit.

There are maybe future plans to support Android and Apple. Until then, the app is free!

Note that the installer is unsigned. This is because certs ain't free. If a warning 
pops up when you try to install it, that's why. It should only happen the first time, 
not on subsequent updates. Regarding those, Coffer checks for a new version on launch, 
and installs only a download that matches the hash published here.

## Your data

Your budget is one file, local to your own machine, at
`%APPDATA%\Coffer`. There is no account and no server (yet).

**Menu → Export** writes the whole budget to spreadsheets.
**Menu → Import** reads them back.
You can import/export all or part of your data (plan, transactions, etc.)

## The details

- **Lines** These are basically envelopes, though I like to call them budget lines.
  Income is allocated across them, spending comes out of them, and each has its own balance and history.
- **Plans** Income allocations to your lines. You can also assign bills to a line to
  keep track of them.
- **Ledger** Your transactions. You can split an expense across multiple lines. You
  can record transactions that aren't finalized, e.g. if you expect the money back.
  Over time, these build a history that inform your spending habits.
- **Habits** This gives you an idea of how you spend your money. Use it to adjust
  your plan as needed.
- **Wishlist** What else is the point of savings? These aren't lines, but you can
  attach them to a line, and you can even allocate money to them.

Coffer is meant to give you the ability to plan, record, and save your money, but
you can use it any way you like to. No plan? No problem. No wishlist? Look at you,
already satisfied. No transactions? Well, if you want to hide away all your money,
I guess that's fine, too.

## Status

Version 0.5.0 because it's not version 1.0.

To report a problem, open an issue and say what you were doing when it
happened. Screenshots are always helpful. I'll put claude right on it.
