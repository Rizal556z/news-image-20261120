# news-image-20261120 — World News, Friday 20 November 2026

[![make.fun · news-image-20261120](https://make.fun/badge/news-image-20261120.svg)](https://make.fun/bounty/news-image-20261120?utm_source=github&utm_medium=readme&utm_campaign=news-image-20261120)
[![rank](https://make.fun/badge/news-image-20261120/Rizal556z/news-image-20261120/rank.svg)](https://make.fun/bounty/news-image-20261120/leaderboard?utm_source=github&utm_medium=readme&utm_campaign=news-image-20261120)
[![reward](https://make.fun/badge/news-image-20261120/Rizal556z/news-image-20261120/reward.svg)](https://make.fun/bounty/news-image-20261120?utm_source=github&utm_medium=readme&utm_campaign=news-image-20261120)

Entry for the [make.fun bounty "Sum up 20 November's world news in one image"](https://make.fun/bounty/news-image-20261120) — $250 pot, top 50 share.

## The image

A dense one-page news poster for **Friday, 20 November 2026** — "ONE DAY
OF WORLD NEWS, ONE PICTURE", 33 stories across 7 regions — leading with
Russia's mass strike on Kyiv (3 bridges hit, 111 missiles, at least 9
killed), the AI market rout (S&P 500 −3.7%, Nasdaq −5.3%, Taiwan −6.2%)
and Cyclone Akvan hitting Odisha (372,000 evacuated, no deaths reported),
with a UTC timeline, a numbers strip, a 10-story grid, a world map and a
numbered list of stories 14–33 below them. Round 2 rebuilds the round-1
front page as this denser poster, from the same day's news.

## How it works

`main.py` (Python 3.13, pure standard library, no network) copies the
`entry.png` image held in this repository to `/output/entry.png`.
Both grading runs therefore write identical bytes.

```sh
mkdir -p out && MAKEFUN_OUTPUT_DIR=out python3 main.py
```

## License

MIT — see [LICENSE](LICENSE).
