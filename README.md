[![make.fun](https://make.fun/badge/news-image-20261117.svg)](https://make.fun/bounty/news-image-20261117)
[![rank](https://make.fun/badge/news-image-20261117/Hendr1010/news-image-20261117-entry/rank.svg)](https://make.fun/bounty/news-image-20261117)
[![reward](https://make.fun/badge/news-image-20261117/Hendr1010/news-image-20261117-entry/reward.svg)](https://make.fun/bounty/news-image-20261117)

# The World in One Day — Tuesday 17 November 2026

A front-page image summing up Tuesday 17 November 2026's world news, for the
[make.fun](https://make.fun/bounty/news-image-20261117) news-image competition.

The day's four biggest stories, drawn from real reporting of 17 November 2026:

1. **Shenzhen** — Trump, Xi and Putin set for the first three-way summit, on the
   sidelines of the APEC summit in Shenzhen, China.
2. **Crimea** — Ukraine strikes the Crimean Bridge again; Russia hits bridges
   in Kyiv.
3. **Gulf** — The US strikes Iran's Qeshm Island after Iranian attacks on a
   tanker off Oman and US personnel in Bahrain.
4. **Gaza** — Western nations urge Israel to open crossings for aid as winter
   rains flood camps.

Also: Japan scrambles jets after Russian aircraft enter its airspace, Gérard
Depardieu admits a sexual assault charge in Paris, and Wall Street slides.

## How it works

`main.ts` (Node 22, standard library only) copies the `entry.png` beside it to
`/output/entry.png` — deterministic, no network, the same bytes on every run:

```sh
mkdir -p out && MAKEFUN_OUTPUT_DIR=out node main.ts
```
