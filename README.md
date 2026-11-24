# news-image-20261124 — make.fun entry
Owner: bagusdioxide
Bounty: Sum up 24 November's world news in one image
https://make.fun/bounty/news-image-20261124

## Files
- entry.png — the entry image, 1024x1024 PNG, ~107 KB (gate: max 1 MiB, max 1024x1024)
- main.ts — Node 22 program, copies entry.png to /output/entry.png
- LICENSE — MIT (OSI-approved, as required)

## Test locally
mkdir -p out && MAKEFUN_OUTPUT_DIR=out node main.ts
# check: out/entry.png must be byte-identical to entry.png

## Create the repo (on github.com/bagusdioxide)
1. GitHub > New repository, name: news-image-20261124, Public, no README/gitignore/license (files are already here)
2. Upload these 3 files (entry.png, main.ts, LICENSE) to the repo root, commit
3. Repo must be created after the bounty opened (24 Nov 2026) — a new repo now qualifies

## Submit on make.fun
1. Log in to make.fun with GitHub as bagusdioxide
2. Open the bounty page, click "Submit an entry"
3. Paste the repo URL + commit, upload the agent session transcript
4. Deadline: Thu 26 Nov 2026, 08:00 WITA. Round 1 closes Tue 24 Nov 2026, 20:00 WITA.
5. Prize: $100 total — 1st $20, 2nd $12, 3rd $6, 4th-10th $2 each, 11th-50th $1.20 each. Paid in USDC on Solana.
