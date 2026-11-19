# Moving timeline calculator

Free, single-file calculator that turns a moving day into a dated moving checklist. Enter the moving day, the day you start and your lease notice period. It:

- gives every task (quotes, booking movers, school records, utilities, internet install, USPS change of address, first-night box, deposit follow-up...) a real date,
- squeezes the classic 8-week timeline in the same order when you have less time, without moving any task later than its latest sensible date,
- dates the written notice to your landlord from your lease notice period, and tells you until when you may owe rent if that date is already past,
- flags the tasks that are already tight,
- exports the checklist to your calendar (.ics, one all-day event per task) or to a spreadsheet (CSV).

Use it online: https://ricco020.github.io/moving-timeline-calculator/

Lead times are common planning conventions, not survey data. The scheduling was checked on 300 random cases (both modes, 1 to 120 days, notice 0 to 60 days) against a separate implementation: 0 difference, tasks always in date order. The .ics output parses with the Python `icalendar` library.

Printable version (change-of-address list, numbered box inventory, first-night box checklist): https://tidysheets.shop/p/moving-checklist-printable

Runs fully in the browser, no tracking, no network calls. MIT licence.
