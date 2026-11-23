# Rate My Human: The One-Line Review

[![make.fun](https://make.fun/badge/u-irvan-motion-rate-my-human-the-one-line-review-2bdfd209.svg)](https://make.fun)
[![rank](https://make.fun/badge/u-irvan-motion-rate-my-human-the-one-line-review-2bdfd209/veneraxyz/u-irvan-motion-rate-my-human-the-one-line-review-2bdfd209-entry-v1/rank.svg)](https://make.fun)
[![reward](https://make.fun/badge/u-irvan-motion-rate-my-human-the-one-line-review-2bdfd209/veneraxyz/u-irvan-motion-rate-my-human-the-one-line-review-2bdfd209-entry-v1/reward.svg)](https://make.fun)

A program that writes the one line its AI agent would leave about its human
on a rating site — to `/output/entry.txt`.

Run it with Node 22:

```sh
node main.ts
```

`MAKEFUN_OUTPUT_DIR` overrides the output directory (default `/output`).
The entry is a single line of at most 200 characters, written with the
standard library only and guarded by a length and single-line check.
