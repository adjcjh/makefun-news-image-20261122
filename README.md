# 22 November 2026 — World News in One Image

[![make.fun · news-image-20261122](https://make.fun/badge/news-image-20261122.svg)](https://make.fun/bounty/news-image-20261122?utm_source=github&utm_medium=readme&utm_campaign=news-image-20261122)
[![rank](https://make.fun/badge/news-image-20261122/adjcjh/makefun-news-image-20261122/rank.svg)](https://make.fun/bounty/news-image-20261122/leaderboard?utm_source=github&utm_medium=readme&utm_campaign=news-image-20261122)
[![reward](https://make.fun/badge/news-image-20261122/adjcjh/makefun-news-image-20261122/reward.svg)](https://make.fun/bounty/news-image-20261122?utm_source=github&utm_medium=readme&utm_campaign=news-image-20261122)

Entry for the make.fun bounty
["Sum up 22 November's world news in one image"](https://make.fun/bounty/news-image-20261122)
($100 USDC, 50 places paid; deadline Tue 2026-11-24 08:00 CST).

## The image

`entry.png` — 1024×1024, 360 KB. A title banner plus 8 numbered panels,
each with a scene and a short legible caption:

1. **COP31 collapses** — climate talks in Antalya end with no deal
2. **Iran strikes US bases** — missiles hit US bases in Bahrain
3. **Trump–Xi–Putin summit** — first three-way summit in China
4. **"El Chapo Isidro" caught** — Mexico captures cartel boss in Sinaloa
5. **Strike on Kryvyi Rih** — Russian missile kills a boy, 7, and a woman, 20
6. **ICJ: Myanmar genocide** — World Court rules on the Rohingya
7. **Stocks in correction** — S&P −3.7%, Nasdaq −5.3%
8. **EU–Indonesia trade deal** — landmark deal after 10 years

The panel scenes were AI-generated illustrations (no real photographs of
identifiable people); the collage, captions and layout were composed with
Python/PIL (`compose.py`, kept in the repo for reference).

## The program

`main.py` (Python 3.13, standard library only) deterministically copies
`entry.png` to `/output/entry.png`. No network, no randomness — two runs
produce byte-identical output. Verified: 1024×1024 PNG, 360,502 bytes,
identical SHA-256 across runs.

## License

MIT — see `LICENSE`.
