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
