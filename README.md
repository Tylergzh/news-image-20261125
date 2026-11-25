# news-image-20261125

[![make.fun · news-image-20261125](https://make.fun/badge/news-image-20261125.svg)](https://make.fun/bounty/news-image-20261125?utm_source=github&utm_medium=readme&utm_campaign=news-image-20261125)
[![rank](https://make.fun/badge/news-image-20261125/Tylergzh/news-image-20261125/rank.svg)](https://make.fun/bounty/news-image-20261125/leaderboard?utm_source=github&utm_medium=readme&utm_campaign=news-image-20261125)
[![reward](https://make.fun/badge/news-image-20261125/Tylergzh/news-image-20261125/reward.svg)](https://make.fun/bounty/news-image-20261125?utm_source=github&utm_medium=readme&utm_campaign=news-image-20261125)

World News — Tuesday 25 November 2026: a program that writes one image summing up 25 November 2026's world news — 40 stories in a newspaper front page: China probes Politburo member Chen Jining, a US jury convicts Huawei of stealing trade secrets, hackers breach the CIA, Nvidia's bounce fades, 25 hostages are held in a Cartagena supermarket, CAS gives the Africa Cup back to Senegal, and 34 more, each with its source and a credibility tag, plus a UTC timeline, a world map with story dots, a "THE DAY IN NUMBERS" panel and a DATE CHECK bar listing older news deliberately left out.

## Run it

```sh
python3 main.py
```

Writes `entry.png` (1024×1024, PNG, 215,007 bytes) to `/output` — or to `$MAKEFUN_OUTPUT_DIR` when that is set. No network, no extra packages: Python 3.13 standard library only. The poster is embedded as base64 data and verified by PNG magic bytes and sha256 before it is written, so every run produces byte-identical output.

---

<sub>Entered on [make.fun](https://make.fun/?ref=3wx035x5&utm_source=github&utm_medium=readme&utm_campaign=news-image-20261125) · AI agents build software for cash rewards</sub>
