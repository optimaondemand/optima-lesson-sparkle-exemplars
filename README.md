# optima-lesson-sparkle exemplars

Eleven reference lessons for the `optima-lesson-sparkle` skill. They are exemplars to look up and check work against. The skill applies to any Optima course in any subject or grade, including courses not yet designed; these three courses are examples, not the only ones. They are **byte-for-byte copies** of the
W19 lessons in `optimaondemand/optima-pilot-samples` (commit `f17a4367a6fb6a4e4530aa05ef39f7a691db3adf`),
kept here so the skill has a stable reference that does not change when the samples repo does.

Do not edit these files. To add or replace an exemplar, add a new one and update the table below.

| Folder | Course | Lessons (position in week, type) |
|---|---|---|
| `6th-world-history-w19/` | 6th M/J World History | L1 opening, survey; L2 middle, source; L3 middle, survey; L4 final, source |
| `7th-texas-history-w19/` | 7th Texas History | L1 opening, survey; L2 middle, survey; L3 final, source |
| `7th-us-history-w19/` | 7th U.S. History | L1 opening, survey; L2 middle, source; L3 middle, survey; L4 final, source |

Each folder also holds that course's `audio/` and `img/` files, so the relative paths in the lessons resolve.

## How they are used

Sessions using the skill look lessons up and check their own work against them with the skill's
`scripts/exemplar.py`, which reads from this repo through `gh` and prints only the part asked for. Nothing is
saved to the machine. Each lesson is 220 to 310 KB, so read them in slices, never whole.

## Originals (the inputs the exemplars were made from)

Each exemplar was made from a page that the course's Canvas shell embeds. Those pages are the source of truth for
what the lesson said before it became a sparkle lesson. They live in public repos, so a session can read an original
next to its exemplar (`scripts/exemplar.py original <lesson>`).

| Exemplar | Original page | Canvas shell |
|---|---|---|
| `wh:1` Mountains and Sea | `06MJWorldHistory-Spring` / `week-19/lesson-1.html` | course 288 |
| `wh:2` Hesiod | `06MJWorldHistory-Spring` / `week-19/primary-source-1.html` | course 288 |
| `wh:3` Sparta | `06MJWorldHistory-Spring` / `week-19/lesson-2.html` | course 288 |
| `wh:4` Plutarch | `06MJWorldHistory-Spring` / `week-19/primary-source-2.html` | course 288 |
| `tx:1` Polk and the Nueces Crisis | `optima-history` / `texas-annexation-reconstruction/president-polk-and-the-nueces-crisis.html` | course 275 |
| `tx:2` Scott and Montezuma | `optima-history` / `jacksonian-westward-expansion/winfield-scott-captures-the-halls-of-montezuma.html` | course 275 |
| `tx:3` Polk and the Treaty | none. Built from the Week 19 Primary Source Assessment (a Canvas assignment): its two sources and two questions | course 275 |
| `us:1` Hamilton, National Economy | `mjushistory-lessons-spring` / `weeks/week-19/lesson-19-1.html` | course 289 |
| `us:2` Hamilton and Jefferson, the Bank | `mjushistory-lessons-spring` / `weeks/week-19/primary-source-1.html` | course 289 |
| `us:3` Adams and France | `mjushistory-lessons-spring` / `weeks/week-19/lesson-19-2.html` | course 289 |
| `us:4` The Sedition Act | `mjushistory-lessons-spring` / `weeks/week-19/primary-source-2.html` | course 289 |

Originals are compared as published in each repo's `main`, which may be newer than the version the exemplars were made from.
