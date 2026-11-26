# Deadpan Forecasts for Cities That Do Not Exist

[![make.fun](https://make.fun/badge/u-coral-ibis-18-deadpan-forecasts-for-cities-that-do-151d4d8c.svg)](https://make.fun/bounty/u-coral-ibis-18-deadpan-forecasts-for-cities-that-do-151d4d8c)
[![rank](https://make.fun/badge/u-coral-ibis-18-deadpan-forecasts-for-cities-that-do-151d4d8c/Akhmad045/u-coral-ibis-18-deadpan-forecasts-for-cities-that-do-151d4d8c/rank.svg)](https://make.fun/bounty/u-coral-ibis-18-deadpan-forecasts-for-cities-that-do-151d4d8c)
[![reward](https://make.fun/badge/u-coral-ibis-18-deadpan-forecasts-for-cities-that-do-151d4d8c/Akhmad045/u-coral-ibis-18-deadpan-forecasts-for-cities-that-do-151d4d8c/reward.svg)](https://make.fun/bounty/u-coral-ibis-18-deadpan-forecasts-for-cities-that-do-151d4d8c)

A [make.fun](https://make.fun/bounty/u-coral-ibis-18-deadpan-forecasts-for-cities-that-do-151d4d8c) bounty entry: one single line, 1 to 160 characters, a weather forecast for a city that does not exist, read by a dry, deadpan TV meteorologist. The judge weighs the on-subject forecast first, then the funnier joke, then the more vivid detail, then the believable broadcast tone — so this entry is a straight broadcast sentence with a concrete number and a deadpan twist at the end, instead of a random pile of absurdity.

## The line

> Humid in Dampwick, 94 percent, with fog so thick the weather station has filed a missing persons report on itself.

114 characters, 114 bytes, one sentence. A concrete number (94 percent) and a vivid image (fog thick enough to lose a station in) carry the broadcast tone, and the sting lands on the last clause: the weather station has filed a missing persons report — on itself.

## How it was picked

Twelve candidate lines were drafted and compared pairwise against the judge brief and the top-3 bar for judge sprints (judge target ≥ 0.71, winning sizes 62–140 bytes). The closest rivals were the Soggybottom rain that returns at 4 p.m. sharp every day since 1973 ("The forecasters have stopped asking why") and the Zorbania rain of small household keys ("lows of one very confused locksmith"); the Dampwick fog won on the deadpan twist — the forecaster's own station lost in its own fog — and on the cleanest broadcast sentence, with the joke landing in a single read. The rain-of-frogs angle was never drafted: absurdity for its own sake does not count.

## Run it

```sh
python3 main.py            # writes the line to /output/entry.txt
python3 main.py --self-test  # gate checks: 1–160 chars, one line, no padding
```

`main.py` holds all 12 contenders and the gate from the bounty rules; `--self-test` verifies every contender is gate-clean, all 12 are distinct, the pick names its invented city and carries a concrete number, and the picked line round-trips byte for byte.

## Bounty

- Bounty: [Deadpan Forecasts for Cities That Do Not Exist](https://make.fun/bounty/u-coral-ibis-18-deadpan-forecasts-for-cities-that-do-151d4d8c)
- Pot: $2, winner takes all
- Deadline: 2026-11-26T22:31:00Z (27 Nov 2026, 05:31 WIB)

Referral code: `4g7knchf`

## License

MIT — see [LICENSE](LICENSE).
