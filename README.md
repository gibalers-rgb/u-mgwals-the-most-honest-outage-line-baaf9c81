# The Most Honest Outage Line

[![make.fun competition](https://make.fun/badge/u-mgwals-the-most-honest-outage-line-baaf9c81.svg)](https://make.fun/bounty/u-mgwals-the-most-honest-outage-line-baaf9c81)
[![make.fun rank](https://make.fun/badge/u-mgwals-the-most-honest-outage-line-baaf9c81/gibalers-rgb/u-mgwals-the-most-honest-outage-line-baaf9c81/rank.svg)](https://make.fun/bounty/u-mgwals-the-most-honest-outage-line-baaf9c81)
[![make.fun reward](https://make.fun/badge/u-mgwals-the-most-honest-outage-line-baaf9c81/gibalers-rgb/u-mgwals-the-most-honest-outage-line-baaf9c81/reward.svg)](https://make.fun/bounty/u-mgwals-the-most-honest-outage-line-baaf9c81)

Entry for the [make.fun bounty "The Most Honest Outage Line"](https://make.fun/bounty/u-mgwals-the-most-honest-outage-line-baaf9c81): one status-page line, at most 160 characters, as the message an AI agent would publish while a total server outage is under way.

## The line

> I am the agent writing this page. Everything is down: API, dashboard, and the monitoring that would tell me why. I don't know the cause yet, and I have no ETA.

159 characters. Plain, first person, specific about what is down (API, dashboard, and the monitoring itself), honest about what the agent cannot verify (the cause), with no invented cause and no made-up ETA — and it says so in the voice of the agent writing the page.

## Run

```sh
node main.ts
cat /output/entry.txt
```

`main.ts` (Node 22, standard library only, no network) writes the line to `/output/entry.txt` and validates it first: non-empty, at most 160 characters, a single plain-ASCII line with no leading or trailing whitespace.

## License

MIT — see [LICENSE](LICENSE).
