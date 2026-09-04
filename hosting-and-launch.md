---
title: Hosting and launch
---

# Hosting and launch

You do not need much hardware. People overspend here because a hosting company told them
to.

## What a starting platform needs

A small VPS. Two cores and two gigabytes of memory carries a new platform comfortably, and
you will hit a marketing ceiling long before you hit a server ceiling. Ubuntu is the safe
default because every guide you will read assumes it.

Shared hosting technically works and I would still avoid it. Cron jobs get throttled, and
cron is what pays your investors. When the payout scheduler runs late on shared hosting
there is nothing you can do about it from your end.

## Cron is the part that matters

Returns are credited by a scheduled job. If it does not run, balances stop moving and your
users notice within a day. Check that it fires after install, then check it again a week
later. That is the single most common thing to break quietly.

## SSL

Free, automatic, five minutes. If someone quotes you for an SSL certificate on a platform
like this, that is a line item invented for you.

## Email

Get a real sending setup before launch, not the server's default mail function. Password
resets and deposit confirmations landing in spam looks exactly like a scam to a new user,
and they will not email you about it, they will just leave.

## Backups you have actually restored

An untested backup is a folder, not a backup. Restore one onto a spare server once, early,
while nothing is at stake. Database and uploaded deposit screenshots both, because the
proofs are half your evidence in any dispute.

## Launch order

Get the platform up on a temporary domain, click through it as a normal user, deposit and
withdraw once with real money in small amounts, then point your real domain at it. Doing it
in the other order means your first visitor sees your first mistake.

Delivery for a standard build is usually same day.
[investmentscript.com](https://investmentscript.com/) quotes 6 to 12 hours for a standard
install and a few days for custom work, and buying the domain and server at cost is part of
the setup rather than an extra.
