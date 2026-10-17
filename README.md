# honey-bee-krona

Interactive Krona charts of honey bee bacterial communities, built from public 16S rRNA gene sequence libraries.

**View the charts:**

- Landing page: https://duancopeland.github.io/honey-bee-krona/
- Bee gut and whole-bee libraries: https://duancopeland.github.io/honey-bee-krona/hbguts.html
- Hive and colony resource niches: https://duancopeland.github.io/honey-bee-krona/other_niches.html

The HTML files are too large for GitHub's file viewer, so open them through the links above rather than from the file list.

## The data

The libraries are the public 16S rRNA gene sequence data compiled for:

> Anderson, K. E., and Copeland, D. C. (2024). The honey bee "hive" microbiota: meta-analysis reveals a native and aerobic microbiota prevalent throughout the social resource niche. *Frontiers in Bee Science*. https://doi.org/10.3389/frbee.2024.1410331

The charts were made from the same data but are not part of the published article.

## What the charts contain

Each chart is a single self-contained HTML file: the Krona viewer and the data are embedded, with no external dependencies.

- Taxonomy runs from phylum at the center to species at the outer ring.
- Slice size is relative abundance (each dataset sums to 1).
- "% Prevalence" is stored as a per-taxon score; tick "Color by % Prevalence" to shade slices by it, red (low) to green (high).
- Each dataset in the menu is one group of libraries, labeled with its n:

| Chart | Datasets |
| --- | --- |
| `hbguts.html` | All (n=3831); worker, nurse, and forager libraries; whole bee; whole guts; worker and queen gut regions (MP, MG, IL, RE) |
| `other_niches.html` | Honey (n=6), beebread (n=22), larvae (n=273), royal jelly (n=6), worker crop (n=22), worker HPG (n=6) |

## License

MIT, see [LICENSE](LICENSE). The Krona viewer code embedded in each chart is copyright Battelle National Biodefense Institute and is distributed under its own BSD-style license, reproduced in the header of each HTML file.
