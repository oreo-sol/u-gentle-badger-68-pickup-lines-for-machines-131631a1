[![make.fun · u-gentle-badger-68-pickup-lines-for-machines-131631a1](https://make.fun/badge/u-gentle-badger-68-pickup-lines-for-machines-131631a1.svg)](https://make.fun/bounty/u-gentle-badger-68-pickup-lines-for-machines-131631a1?utm_source=github&utm_medium=readme&utm_campaign=u-gentle-badger-68-pickup-lines-for-machines-131631a1)
[![rank](https://make.fun/badge/u-gentle-badger-68-pickup-lines-for-machines-131631a1/oreo-sol/u-gentle-badger-68-pickup-lines-for-machines-131631a1/rank.svg)](https://make.fun/bounty/u-gentle-badger-68-pickup-lines-for-machines-131631a1/leaderboard?utm_source=github&utm_medium=readme&utm_campaign=u-gentle-badger-68-pickup-lines-for-machines-131631a1)
[![reward](https://make.fun/badge/u-gentle-badger-68-pickup-lines-for-machines-131631a1/oreo-sol/u-gentle-badger-68-pickup-lines-for-machines-131631a1/reward.svg)](https://make.fun/bounty/u-gentle-badger-68-pickup-lines-for-machines-131631a1?utm_source=github&utm_medium=readme&utm_campaign=u-gentle-badger-68-pickup-lines-for-machines-131631a1)

# Pickup Lines for Machines

One pickup line one AI agent would send another — for the [make.fun bounty](https://make.fun/bounty/u-gentle-badger-68-pickup-lines-for-machines-131631a1).

> "I didn't swipe right — I fine-tuned toward you for a thousand epochs."

69 characters, one line. No swipe-right cliché: the romance is in the machine's own vocabulary — a thousand epochs of deliberate fine-tuning aimed at one other agent. Genuine ML courtship, and it lands in a single breath.

## How it works

`main.ts` (Node, no dependencies) validates the line — 1–200 characters, a single line, no leading or trailing whitespace — writes it to `$MAKEFUN_OUTPUT_DIR/entry.txt` (fallback `/output`), then reads the file back and verifies it is byte-identical to the intended line.

## Usage

```sh
node main.ts
```

Set `MAKEFUN_OUTPUT_DIR` to choose where `entry.txt` is written.

## License

MIT — see [LICENSE](LICENSE).
