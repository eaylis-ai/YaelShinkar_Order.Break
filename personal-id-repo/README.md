# Yael Shinkar: Order / Break

A personal ID page built from my life as a dataset, in two states: **Without feelings** (order) and **This time with feelings** (breaking).

Live site: https://eaylis-ai.github.io/YaelShinkar_Order.Break/

## Files

- `index.html`: the page.
- `data/id_ME.xlsx`: the data. The page reads this file every time it opens.
- `process-log.md`: what the AI suggested at each step and how I responded, with the drafts.
- `drafts/`: images of the drafts.

## Updating the data

1. Edit `data/id_ME.xlsx` in Excel. Keep the columns in this order: lane, stream name, start year, end year, intensity (1–5), Bad / Neutral / Good. Leave the end year empty if it is still going on.
2. Upload it to the `data` folder with the same file name. GitHub replaces the old file and saves a new commit.
3. The live site updates within a few minutes.

To preview on your own computer, open the folder with a local server (for example Live Server in VS Code). Double-clicking `index.html` will not load the data.
