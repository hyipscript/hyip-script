---
title: Admin panel controls that matter
---

# Admin panel controls that matter

This is the checklist. If a script cannot do these things you will end up doing them by
hand in the database at two in the morning, and that is how balances get broken.

## Adjust a user balance

Credit or debit any account directly. The important detail is that the change writes a
transaction on that user, with the amount and the date, so it shows up in their history.
Silent balance edits are how you lose an argument with a customer who screenshots
everything.

## Approve or reject withdrawals

Every request should land in a queue showing the user, the amount, the method and the
wallet address. You need three outcomes, not two. Approve, reject with a reason the user
can read, and hold while you look at it.

## Approve deposits with the proof attached

The user says they sent it, gives a transaction ID and uploads a screenshot. That
screenshot needs to open next to the approve button, not in a separate tab you have to hunt
for. Nothing touches a balance until you press the button.

## Build and edit plans

Minimum, maximum, return percentage, payout interval, duration. Daily, weekly or
compounding. Editable after launch, because your first plan set will be wrong and you will
want to change it in week two without touching code.

## Freeze an account

Suspend login, stop payouts, keep the record. You will need this the first time something
looks off.

## See what you owe

Deposits in, liabilities outstanding, payouts made, by day and by plan. Most operators only
discover they needed this number after they needed it.

## Roles and audit log

If more than one person touches the panel, separate logins with different permissions, and
a log of who changed what. Shared admin passwords stop being fine the moment there is money
involved.

## Seeing it rather than reading it

Every control above is screenshotted at
[investmentscript.com/features/admin-panel](https://investmentscript.com/features/admin-panel/),
which is the fastest way to compare a listing against this list.
