# Apple M1 to M6 benchmarks

Interactive chart of Geekbench 7 (CPU single-core, multi-core, Metal GPU), Cinebench 2026 and Cinebench 2024 scores for every Apple Silicon chip from M1 to M6, plus a full results table.

Live: https://bpetrynski.github.io/apple-m-chips-benchmarks/

Each view has its own link: `#gb-multi`, `#gb-single`, `#gb-metal`, `#cb26-multi`, `#cb26-single`, `#cb24-multi`, `#cb24-single`.

## Data

Best-scoring configuration per chip, data as of November 2026.

- Geekbench 7: [Geekbench Browser, Mac Benchmarks](https://browser.geekbench.com/mac-benchmarks)
- Cinebench 2026 / 2024: [cpu-monkey.com](https://www.cpu-monkey.com/), gaps filled from [notebookcheck.net](https://www.notebookcheck.net/); M1 Ultra Cinebench 2026 multi-core is an estimate from [Drop & Render](https://dropandrender.com/cinebench-benchmarks)

All numbers live in the `<table>` in `index.html`; the chart reads them from there. To update a score, edit the cell's `data-v` and its text. The "Key takeaways" and "Common comparisons" sections are static text (for search engines), so update their numbers too.

Layout inspired by the chart by u/AlborzDesign.

## Static images

`images/` has PNG versions of the charts (Reddit / social posts): Geekbench 7 multi-core + Metal, single-core (axis from 0 and from 2,000), Cinebench 2024, Cinebench 2026 multi-core and single-core, plus a results table.

## Hosting

Single static `index.html`, no build step. GitHub Pages: Settings → Pages → Deploy from a branch → `main` / `/ (root)`.
