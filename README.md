# news-image-20261120 — World News, Friday 20 November 2026

[![make.fun · news-image-20261120](https://make.fun/badge/news-image-20261120.svg)](https://make.fun/bounty/news-image-20261120?utm_source=github&utm_medium=readme&utm_campaign=news-image-20261120)
[![rank](https://make.fun/badge/news-image-20261120/Rizal556z/news-image-20261120/rank.svg)](https://make.fun/bounty/news-image-20261120/leaderboard?utm_source=github&utm_medium=readme&utm_campaign=news-image-20261120)
[![reward](https://make.fun/badge/news-image-20261120/Rizal556z/news-image-20261120/reward.svg)](https://make.fun/bounty/news-image-20261120?utm_source=github&utm_medium=readme&utm_campaign=news-image-20261120)

Entry for the [make.fun bounty "Sum up 20 November's world news in one image"](https://make.fun/bounty/news-image-20261120) — $250 pot, top 50 share.

## The image

A newspaper front page for **Friday, 20 November 2026**, leading with the
Iran war (cost $48.3 billion and rising) and the Strait of Hormuz oil
story (Brent ~$91), with the day's other top stories readable below it:

- Kyiv struck overnight (Russia's strike on the capital)
- ICJ rules 9–6 that Myanmar committed genocide against the Rohingya
- Denmark's parliament approves the Greenland–US security pact 109–0
- NYC Mayor Mamdani announces Rikers Island will close by 2032
- US Senate rejects the war-powers resolution 51–48

## How it works

`main.py` (Python 3.13, pure standard library, no network) copies the
`entry.png` image held in this repository to `/output/entry.png`.
Both grading runs therefore write identical bytes.

```sh
mkdir -p out && MAKEFUN_OUTPUT_DIR=out python3 main.py
```

## License

MIT — see [LICENSE](LICENSE).
