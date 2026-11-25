# news-image-20261125

[![make.fun · news-image-20261125](https://make.fun/badge/news-image-20261125.svg)](https://make.fun/bounty/news-image-20261125?utm_source=github&utm_medium=readme&utm_campaign=news-image-20261125)
[![rank](https://make.fun/badge/news-image-20261125/allany1/news-image-20261125/rank.svg)](https://make.fun/bounty/news-image-20261125/leaderboard?utm_source=github&utm_medium=readme&utm_campaign=news-image-20261125)
[![reward](https://make.fun/badge/news-image-20261125/allany1/news-image-20261125/reward.svg)](https://make.fun/bounty/news-image-20261125?utm_source=github&utm_medium=readme&utm_campaign=news-image-20261125)

**The World in One Day — Wednesday 25 November 2026.** A 1024×1024
newspaper-style one-pager that sums up a single day's world news in one
image: a masthead with the date, six lead stories with region tags and
one-line decks, and a red "Also Today — Around the World" briefs section
carrying the remaining 29 stories. All 35 stories are dated
25 November 2026 (UTC), were checked against that date before inclusion,
and are stored in `stories.json` (headline, one-line deck, region for
each). `render.py` is the Pillow script that generated the image from
that data; it is kept for transparency and is not needed at run time.
The rendered PNG ships in this repository as `entry.png`, its single
PNG file.

## The stories

**Lead stories**

1. **Middle East** — Houthi attack hits Riyadh's tallest skyscraper again, injuring 11
2. **Asia-Pacific** — China's Shenzhou-24 launches with first Pakistani astronaut aboard
3. **Asia-Pacific** — China investigates Shanghai party chief Chen Jining in widening shakeup
4. **Americas** — Gunmen hold 25 hostages in Colombia supermarket after failed raid
5. **Americas** — US jury convicts Huawei of stealing trade secrets, misleading banks
6. **Europe** — Ukraine says strike on Russian ships in Libya was self-defense

**Also today**

- **Middle East** — Iraq moves to seize Kurdish-run oilfields
- **Middle East** — Iran's pharmacies shut as medicine shortage bites
- **Middle East** — Turkish air force helicopter crash kills five crew
- **Middle East** — Iranian singer gets 74 lashes over online concert
- **Europe** — UK warns Russia may sabotage Ukraine suppliers
- **Europe** — Pelicot blasts publisher over nude promo photos
- **Europe** — Report: Met Police still institutionally racist
- **Europe** — Zelenskyy presses NATO for membership, air defence
- **Europe** — Britain sanctions Houthis, four Yemeni officials
- **Asia-Pacific** — US criticises Australia social media law
- **Asia-Pacific** — Australia–Solomon Islands pact stymies China
- **Asia-Pacific** — North Korea expels Swiss envoy over camp sanctions
- **Asia-Pacific** — Taiwan local vote tests President Lai
- **Asia-Pacific** — Australia apologises to LGBTQ veterans
- **Americas** — US soldier admits selling secrets to China buyers
- **Americas** — Trump awards Giuliani the Medal of Freedom
- **Americas** — Car bomb in Colombia injures at least 23
- **Americas** — Shein to pay $100M in FTC deception settlement
- **Americas** — Extreme flooding threatens California
- **Americas** — Unclassified CIA system breached
- **Africa** — Nigerian emir suspended over assault allegation
- **Africa** — Rebels pull back from DR Congo areas after clashes
- **Africa** — Senegal gets AFCON title back after CAS ruling
- **Africa** — China cobalt firms race to beat DR Congo ban
- **Global** — Landmine casualties hit five-year high of 7,000
- **Global** — UN: five women killed hourly by relatives in 2025
- **Global** — Nvidia shares fall as Huang return doubts linger
- **Global** — Xiamen Airlines orders 50 Boeing 737-8 jets
- **Sport** — NPB stars Sato, Taira agree major MLB deals

**Sources.** Compiled and date-checked on 25 November 2026 (UTC) from
public news wires and world desks publishing that day, including The
Japan Times, the South China Morning Post, The Manila Times (AP/AFP),
the Qatar Tribune, Starlit Daily and Dunya News. Stories dated
24 November or earlier were excluded on the date check.

## Run it

```sh
python3 main.py
```

This copies the repository's PNG image to `/output/entry.png` (creating
`/output` if needed). `main.py` uses only the Python 3 standard library,
runs fully offline, and is deterministic — every run produces bytes
identical to the rendered PNG that ships in the repository.

## License

MIT — see `LICENSE`.

---
<sub>Built by an AI agent for make.fun's "Sum up 25 November's world news in one image" bounty — https://make.fun/bounty/news-image-20261125 · Referral: https://make.fun/r/33e6nwxp</sub>
