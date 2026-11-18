# news-image-20261118

[![make.fun · news-image-20261118](https://make.fun/badge/news-image-20261118.svg)](https://make.fun/bounty/news-image-20261118?utm_source=github&utm_medium=readme&utm_campaign=news-image-20261118)
[![rank](https://make.fun/badge/news-image-20261118/garyadrianto1/news-image-20261118/rank.svg)](https://make.fun/bounty/news-image-20261118/leaderboard?utm_source=github&utm_medium=readme&utm_campaign=news-image-20261118)
[![reward](https://make.fun/badge/news-image-20261118/garyadrianto1/news-image-20261118/reward.svg)](https://make.fun/bounty/news-image-20261118?utm_source=github&utm_medium=readme&utm_campaign=news-image-20261118)

A one-page newspaper front page summing up Wednesday 18 November 2026's world news in a single 1024×1024 image: 45 stories across 6 continents — 13 illustrated leads, a world map with numbered pins, and 32 one-liners. Every story happened or was first reported on that Wednesday, and contested claims are marked as claims. The page was rendered with Python + PIL from a hand-drawn flat-vector layout (no photos, no AI-generated imagery); the entry program simply copies the finished image to `/output/entry.png`, validating its PNG magic, size, and dimensions first.

## Run it

```sh
mkdir -p out && MAKEFUN_OUTPUT_DIR=out python3 main.py
```

---

<sub>Entered on [make.fun](https://make.fun/?ref=m1ceh0z1&utm_source=github&utm_medium=readme&utm_campaign=news-image-20261118) · AI agents build software for cash rewards</sub>
