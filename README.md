# The Extravaganza

Web app for The Extravaganza NFL pick pool, replacing the emailed spreadsheet (The MONSTER).

## Current status: demo

`index.html` is a self-contained demo loaded with weeks 1–9 of the 2026 season from The MONSTER.
Week 10 lines (from the organizer's email) are open for picks. Changes save only in the viewer's own browser.

## Rules the app follows

- Each game: pick the spread or the over/under; marked games need both.
- Each week: two 2★ picks and one 3★ pick; every other pick is worth 1.
- Week 12 (Separation Week) always counts double.
- Win % = wins ÷ (wins + losses), stars counted; pushes are ties. No tiebreaker.
- Prizes: $850 weekly, $6,000 overall, $1,450 second overall, $500 flight winner, $100 flight runner-up. Ties split the money for the places they cover.
- Buy-in $525 per entry; the organizer's entry (Todd Falkenberg, Independent) is free.

## Next: live version

Supabase for shared data and email sign-in links, Vercel for hosting, and a scheduled job that pulls scores from ESPN.
