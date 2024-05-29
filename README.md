# GameDB-Genesis
Sega Genesis, part of [GameDB](https://github.com/niemasd/GameDB).

## Structured Downloads
* **[`Genesis.data.json`](https://github.com/niemasd/GameDB-Genesis/releases/latest/download/Genesis.data.json):** All data, structured in the JSON format
* **[`Genesis.data.tsv`](https://github.com/niemasd/GameDB-Genesis/releases/latest/download/Genesis.data.tsv):** All data, structured in the TSV format
* **[`Genesis.release_dates.pdf`](https://github.com/niemasd/GameDB-Genesis/releases/latest/download/Genesis.release_dates.pdf):** Histogram of release dates, stratified by region
* **[`Genesis.titles.json`](https://github.com/niemasd/GameDB-Genesis/releases/latest/download/Genesis.titles.json):** Mapping of serial numbers to game titles, structured in the JSON format

# Notes

## Uniquely Identifying Games

The game folders in [`games`](games) are named after their serial, which is at offsets `0x180` through `0x18D` (inclusive) of the ROM, and which can be used to uniquely identify the game.

# Sources
* [No-Intro](https://no-intro.org/)
