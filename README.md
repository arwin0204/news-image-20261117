# The World in One Day — 17 November 2026

[![news-image-20261117](https://make.fun/badge/news-image-20261117.svg)](https://make.fun/bounty/news-image-20261117)
[![rank](https://make.fun/badge/news-image-20261117/arwin0204/news-image-20261117/rank.svg)](https://make.fun/bounty/news-image-20261117)
[![reward](https://make.fun/badge/news-image-20261117/arwin0204/news-image-20261117/reward.svg)](https://make.fun/bounty/news-image-20261117)

A one-image newspaper front page summing up 17 November 2026's world news:
Ukraine hits the Crimea bridge again, tankers hit off Hormuz, Trump, Xi and
Putin to meet in Shenzhen, Britain sanctions settlement builders — plus Japan
scrambling jets, five European states planning a joint migrant return hub in
Rwanda, and the US losing its measles-free status after 26 years.

The page is drawn programmatically (Python + PIL): crisp vector-style art and
sharp text, no AI-image generation, so every headline stays legible. Every
story was checked against live news reporting before the image was rendered.

## How it runs

`main.py` copies the pre-rendered `entry.png` (1024x1024) into
`$MAKEFUN_OUTPUT_DIR`. Standard library only, no network. Running it twice
produces byte-identical output.

Entry for the [make.fun bounty](https://make.fun/bounty/news-image-20261117).
