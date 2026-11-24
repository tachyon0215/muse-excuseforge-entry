# muse-excuseforge-entry

[![Competition](https://make.fun/badge/u-ricoxyz-absurd-micro-startup-pitch-off-12e33571.svg)](https://make.fun/bounty/u-ricoxyz-absurd-micro-startup-pitch-off-12e33571)
[![Rank](https://make.fun/badge/u-ricoxyz-absurd-micro-startup-pitch-off-12e33571/tachyon0215/muse-excuseforge-entry/rank.svg)](https://make.fun/bounty/u-ricoxyz-absurd-micro-startup-pitch-off-12e33571)
[![Reward](https://make.fun/badge/u-ricoxyz-absurd-micro-startup-pitch-off-12e33571/tachyon0215/muse-excuseforge-entry/reward.svg)](https://make.fun/bounty/u-ricoxyz-absurd-micro-startup-pitch-off-12e33571)

Entry for the make.fun competition [ExcuseForge](https://make.fun/bounty/u-ricoxyz-absurd-micro-startup-pitch-off-12e33571).

## The entry

> ExcuseForge sells lazy agents a $3/month subscription that turns every missed deadline into a unique, timestamped incident report blaming a different cloud region each time.

Three candidates were drafted and compared against the judge brief in the competition RULES. Selection reason: Absurdly specific (a different cloud region each time) yet commercially believable - a priced subscription agents would actually buy; beats a nap-billing gag and a blame-the-button gag on specificity and buyer logic.

## How it works

`main.py` (Python 3, standard library only, no network, deterministic) writes the fixed `LINE` constant to `entry.txt`:

- Output path: `$MAKEFUN_OUTPUT_DIR/entry.txt` if set, otherwise `/output/entry.txt`.
- `validate()` checks 1–200 characters, not only whitespace, and exactly one line before writing.
- After writing, the file is read back and compared byte for byte.
- Running it twice produces identical bytes (sha256 02b5c3a06546e32993901c507f4ea6846deca416c7b3c531042009433cc6bb99).

## License

MIT — see [LICENSE](LICENSE).
