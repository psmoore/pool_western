# Western Campus Recreation pool — Pool Relay embed preview

A three-page replica of the pool part of the
[Western Campus Recreation Schedules/Hours page](https://www.uwo.ca/campusrec/schedules/index.html) — the pool
schedule, Fit Lane Swim, and the Saturday Recreation / Women's Only / 2SLGBTQIA+ swims — each with a live
[Pool Relay](https://www.poolrelay.com) calendar.

Not an official Western University page. It says so in a ribbon across the top.

Built with `python3 build.py` (edit it, not the HTML) and served by GitHub Pages.

| Page | Calendar |
|---|---|
| `index.html` — Pool Schedule | [`JZFbwQPB…`](https://www.poolrelay.com/v/JZFbwQPBPYl4stBPd8MkF8) everything in the pool |
| `fit-lane-swim.html` | [`NF0VU594…`](https://www.poolrelay.com/v/NF0VU5945BliG4dBjcG4Ye) Fit Lane Swim and closures |
| `community-swims.html` | [`jqQnktEJ…`](https://www.poolrelay.com/v/jqQnktEJJFMjZallFoztFW) Saturday community swims |

## How the pool is modeled

One 50 m pool with two configurations: **Short Course (25 m)**, split into a Shallow Tank and a Deep Tank, and
**Long Course (50 m)**. The schedule's codes map directly: (S) shallow tank, (D) deep tank, (S/D) both, (LC)
long course. No lane counts are published, so tanks are booked whole.

## Source and what is ours

Fit Lane Swim September 5 – December 23, 2026; Recreation, Women's Only and 2SLGBTQIA+ swims from September 19.
Thanksgiving (Monday, October 12) is closed — from the Reading Week building hours and "closed Western holidays".
Ours: the 2SLGBTQIA+ swim has no tank code and is shown in the shallow tank. The facility is geocoded to
Phillip Aziz Avenue (OpenStreetMap); Western's pages give only the university's 1151 Richmond Street address.

Open questions (also on the pages): Reading Week pool hours · the 2SLGBTQIA+ tank · lanes per tank · December exam-period hours.
