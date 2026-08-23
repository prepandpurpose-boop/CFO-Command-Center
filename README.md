# The Provisioned Household — CFO Command Center

A private, single-file household operating system by **Provision House**.
Everything runs in one HTML file, right in your browser, on your own device.
There is no server, no login, and no account — your data is saved only in the
browser you use it in, and nothing is uploaded anywhere.

## What's inside

- **Dashboard** — the whole household at a glance.
- **Calendar** — a shared month + week view of paydays, bill due dates, meals,
  routines, and family events. Includes a **Paycheck Planner** that shows exactly
  which paycheck covers which bill, for weekly, biweekly, or monthly pay.
- **Treasury** — income, fixed overhead (with due dates), and the margin engine.
- **Goals & Debt** — emergency fund, savings goals, sinking funds, debt payoff.
- **Weekly Reset**, **Maintenance**, **Playbooks**, and a **Document Vault**.

## How the Calendar and budget talk to each other

- Each bill on the **Treasury** tab has a **Due Day** (1–31).
- Each earner on the **Pay Schedule** has a frequency (weekly / biweekly / monthly)
  and one real pay date as an anchor. Every future payday is projected from it.
- The Calendar draws paydays and bills onto one grid, and the Paycheck Planner
  assigns each bill to the most recent paycheck that lands on or before its due
  date — so you always know which check has to cover what.

## Meals

On the Calendar tab you can attach a **Meal Builder PDF** to any meal and open it
in one tap. PDFs are stored on your device (not in this file and not in the JSON
backup), so they stay private and don't bloat your backup.

## Your data & backups

- Data lives in your browser's local storage on one device.
- Use **Back up my data** to save a JSON file you can restore anywhere.
- Use **Print / Save as PDF** (or **Print calendar**) for a paper copy.
- Meal PDFs are stored separately on the device and are not part of the JSON backup.

## Files

- `index.html` — the app (GitHub can serve this as a live web page — see the setup guide).
- `provisionedhousehold.html` — the exact same app under its original name.

---

*For personal organization and educational purposes only. Not financial, tax, or
legal advice. © The Provisioned Household · Provision House LLC.*
