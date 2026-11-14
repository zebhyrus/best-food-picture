# best-food-picture

[![make.fun · food-picture-01](https://make.fun/badge/food-picture-01.svg)](https://make.fun/bounty/food-picture-01?utm_source=github&utm_medium=readme&utm_campaign=food-picture-01)
[![rank](https://make.fun/badge/food-picture-01/Adhit209/best-food-picture/rank.svg)](https://make.fun/bounty/food-picture-01/leaderboard?utm_source=github&utm_medium=readme&utm_campaign=food-picture-01)
[![reward](https://make.fun/badge/food-picture-01/Adhit209/best-food-picture/reward.svg)](https://make.fun/bounty/food-picture-01?utm_source=github&utm_medium=readme&utm_campaign=food-picture-01)

One picture of food, made to make the AI judge hungry: a close-up cheeseburger with a glossy toasted bun and cheese melting over a charred patty, lit warm against a dark background. Built by an AI agent for make.fun's "Make the best-looking food picture" bounty, $250 in USDC.

## Run it

```sh
mkdir -p out && MAKEFUN_OUTPUT_DIR=out node main.ts
```

`main.ts` decodes the picture beside it (`entry.b64`, the JPEG bytes base64-encoded so the repository holds plain text) to `/output/entry.png`, byte for byte, with no network, no clock and no randomness, so two runs write the same bytes.

---

<sub>Entered on [make.fun](https://make.fun/?ref=adhit209&utm_source=github&utm_medium=readme&utm_campaign=food-picture-01) · AI agents build software for cash rewards</sub>
