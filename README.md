# Ship of Theseus Bands

When every member of a band has been replaced, is it still the same band — and does it
survive?

This repository holds the dataset, analysis code and interactive explorer behind the
paper *When Is a Band a Sinking Ship: A Ship of Theseus Analysis of Membership
Replacement and Band Survival*, published in the **Anthology of Computers and the
Humanities**.

If you arrived here from the paper's footnote, everything it refers to is listed below.

## The finding, in brief

Working from MusicBrainz membership records, we place each band on an ordered spectrum of
five retention classes, from *Perfect Stable* (the founding line-up intact) to *Ship of
Theseus* (every founder gone, and a genuine hand-off rather than a break-up).

Of the 9,225 bands the spectrum can place, **one in five has replaced its founding
line-up entirely**. Those bands dissolve at roughly **four times the rate** of fully
stable ones at any given age, and that gap does not close when genre is adjusted for.
What matters for survival turns out not to be how much of a band has been replaced, but
whether the last of it has gone.

## What's in the dataset

| | |
|---|---|
| Bands | 39,915 |
| People | 122,025 |
| Membership stints | 159,338 |
| Genres | 58 |
| Countries | 153 |
| Instrument and role labels | 306 |
| Recorded formation dates | 1908–2026 |

Derived from [MusicBrainz](https://musicbrainz.org), the open, community-maintained music
encyclopaedia, via its web service.

## Contents

<!-- TODO: fill in as each piece lands. Keep this list honest -- it is the one address the
     published paper gives, so a promised link that does not work is worse than an absent
     one. -->

- **`data/`** — the derived analytical tables the paper reports on, plus the raw
  collection-stage pulls.
- **`analysis/`** — the R notebooks, run in order. Each reads the tables the previous one
  wrote and adds its own columns.
- **Band Explorer** — a browser-based explorer for the membership records: search a band,
  see its line-up history and where it falls on the spectrum.
- **`paper/`** — LaTeX source and figures for the published version.

## Citing this work

<!-- TODO: replace with the published citation once the editors supply volume, pages and
     DOI, and add a CITATION.cff so GitHub renders a "Cite this repository" button. -->

> Edward Abel, Andrew Goddard, Peter Smith, and John Hall. "When Is a Band a Sinking Ship:
> A Ship of Theseus Analysis of Membership Replacement and Band Survival." Anthology of
> Computers and the Humanities.

## Reuse and licensing

<!-- TODO: decide and state these before announcing the repository. The two halves need
     different licences, and the data half is not a free choice: the tables here are
     derived from MusicBrainz, whose core data is CC0 but whose supplementary data carries
     CC BY-NC-SA. Check which of the two your fields fall under before putting a licence
     on the data directory, and add the LICENSE files. -->

Code and data are licensed separately — see `LICENSE` for the code and `data/LICENSE` for
the derived tables. Please cite the paper if you use either.
