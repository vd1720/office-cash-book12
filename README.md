# Office Cash Book

A simple petty-cash book for an office: the Boss gives cash, the team logs expenses, client payments go into a shared cash box.

## Try the demo

Open `index.html` (or the GitHub Pages link). Demo data is saved in your browser only.

| Role | Username | Password |
|---|---|---|
| Boss | `boss` | `boss123` |
| Project Manager | `vishwesh` | `vishwesh123` |
| HR | `priya` | `priya123` |

Use **Reset demo data** on the sign-in page to start fresh.

## Features

- Boss overview: one card per person, the cash box card, received vs spent chart, spending by category
- Team portal: own cash in hand, cash box, recent entries, categories, team balances
- Entries: search, filters, edit, delete, copy for Excel
- Cash box: client payments in, team takes cash out
- Team: add people, roles, reset passwords
- Chat between the Boss and the team
- Light and dark mode, mobile bottom bar with a built-in number pad

## Note

This repo runs in **demo mode** (`window.CASHBOOK_DEMO = true`), storing data in the browser.
For real multi-user use it needs a server and database (see the Hetzner plan).
