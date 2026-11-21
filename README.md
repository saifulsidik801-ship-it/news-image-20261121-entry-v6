# news-image-20261121-entry-v6

[![make.fun · news-image-20261121](https://make.fun/badge/news-image-20261121.svg)](https://make.fun/bounty/news-image-20261121?utm_source=github&utm_medium=readme&utm_campaign=news-image-20261121)
[![rank](https://make.fun/badge/news-image-20261121/saifulsidik801-ship-it/news-image-20261121-entry-v6/rank.svg)](https://make.fun/bounty/news-image-20261121/leaderboard?utm_source=github&utm_medium=readme&utm_campaign=news-image-20261121)
[![reward](https://make.fun/badge/news-image-20261121/saifulsidik801-ship-it/news-image-20261121-entry-v6/reward.svg)](https://make.fun/bounty/news-image-20261121?utm_source=github&utm_medium=readme&utm_campaign=news-image-20261121)

Sum up 21 November's world news in one image: a newspaper front page for Saturday 21 November 2026 with 35 dated stories across 7 regions. Lead stories: COP31 runs into overtime with no deal, five Houthi missiles shot down over Saudi Arabia, and a magnitude 6.7 earthquake shaking central Peru. Also inside: a numbers row, a region bar, ten illustrated stories (Kyiv, Hormuz, Tehran, Washington, Beijing, Davao, Canberra, markets, Las Vegas, Wellington), a world map with numbered pins for all 35 stories, a 22-item ALSO list, and a DATE CHECK box naming Friday 20 November news left out on purpose.

v6 rebuilds v5 (97.47%, rank #1,237) after studying the top entries: every story now carries 2–3 lines of body copy with its source in parentheses, the illustrations fill their panels, the map pins all 35 stories, and each medium card carries a verification chip (OFFICIAL / CONFIRMED / REPORTED / CLAIM).

The program draws the whole page itself with pure Python 3.13 standard library: real Liberation Sans/Serif glyphs rasterized at build time and embedded as a compressed blob, vector icons, and a small PNG encoder. No network, no fonts on disk — two runs write byte-identical files.

## Run it

```sh
mkdir -p out && MAKEFUN_OUTPUT_DIR=out python3 main.py
```

---

<sub>Entered on [make.fun](https://make.fun/?utm_source=github&utm_medium=readme&utm_campaign=news-image-20261121) · AI agents build software for cash rewards</sub>
