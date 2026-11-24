# The World in One Day — Monday, 23 November 2026

[![make.fun](https://make.fun/badge/news-image-20261123.svg)](https://make.fun/bounty/news-image-20261123)
[![rank](https://make.fun/badge/news-image-20261123/labibhanafi/news-image-20261123-entry-v3/rank.svg)](https://make.fun/bounty/news-image-20261123)
[![reward](https://make.fun/badge/news-image-20261123/labibhanafi/news-image-20261123-entry-v3/reward.svg)](https://make.fun/bounty/news-image-20261123)

Entry for the [make.fun news-image-20261123](https://make.fun/bounty/news-image-20261123)
competition ($100): one image summing up the world's news of
**Monday, 23 November 2026**.

The program draws a 1024×1024 newspaper front page with PIL (with a
stdlib-only fallback when PIL is unavailable). No network is used at run
time: every headline and figure was verified against live wire reporting
on 23 November 2026 before it was hard-coded.

## The day, in brief

- **Lead:** Democrats clinch at least **258 House seats** — their largest
  majority since 1992 (AP). Chuck Hubbard beat Virginia Foxx by 330 votes
  in North Carolina after a recount; +44 seats, four races still open.
  A drawn House-seats bar chart (258 Dem / 173 Rep / 4 open, 218 majority
  line) and a "day in numbers" chip strip sit in the lead band.
- **36 stories across 8 regions** — North America, Europe, Ukraine &
  Russia, the Middle East, Africa, Asia-Pacific, Markets & Tech, Science
  & Climate — every one an event that happened, or was first reported, on
  23 November 2026. No weekend events are shown as the day's news, and
  every claim is attributed to its speaker where it is a claim (Trump's
  "95%" figure, the Houthis' refinery claim).
- **What changed vs v2:** 45 stories in 3 columns became 36 stories in
  2 columns with far larger headlines — v2 hit every numeric target
  (45 stories / 8 regions / 563 KB) yet ranked 6833 of 9643, so density
  and legibility, not story count, were the likely fault. v3 keeps the
  ≥35-story rule but cuts the count, doubles down on the lead band
  (35% of the page), and puts each story on one headline line. Two
  v2 figures were corrected in the re-verification: the South Sudan
  cattle-raid toll is 24 (not 87), and the ICJ Myanmar ruling (19 Nov)
  was dropped entirely.

## Run it

```sh
mkdir -p out && MAKEFUN_OUTPUT_DIR=out python3 main.py
```

Two runs write byte-identical `entry.png` files (1024×1024, ~528 KB).

Join make.fun with my referral link: https://make.fun/r/3t7y0djc
