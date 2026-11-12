# Ship of Theseus Bands

When every member of a band has been replaced, is it still the same band — and does it
survive?

This repository accompanies the paper *When Is a Band a Sinking Ship: A Ship of Theseus
Analysis of Membership Replacement and Band Survival*, to be presented at **CHR 2027** and
published in the **Anthology of Computers and the Humanities**.

> **Status.** The conference has not taken place yet. The dataset, the analysis code and
> the interactive Band Explorer are being prepared for release here to coincide with
> publication. Watch the repository to be notified.

## The idea

The Ship of Theseus paradox asks whether an object remains the same object once all its
parts have been replaced. In a band the parts are people: line-ups turn over one member at
a time, sometimes until none of the founders remain, and every change can be dated.

That makes it a question you can measure rather than only argue about. We place each band
on an ordered spectrum of five retention classes, from *Perfect Stable* — the founding
line-up intact — to *Ship of Theseus*, where every founder has gone and the band carried on
through a genuine hand-off rather than a break-up.

## What we found

Of the 9,225 bands the spectrum can place, **one in five has replaced its founding line-up
entirely**. Those bands dissolve at roughly **four times the rate** of fully stable ones at
any given age, and the gap does not close when genre is adjusted for.

Survival turns not so much on how much of a band has been replaced as on whether the last
of it has gone.

## The dataset

Built from [MusicBrainz](https://musicbrainz.org), the open, community-maintained music
encyclopaedia.

| | |
|---|---|
| Bands | 39,915 |
| People | 122,025 |
| Membership stints | 159,338 |
| Genres | 58 |
| Countries | 153 |
| Instrument and role labels | 306 |
| Recorded formation dates | 1908–2026 |

## Coming here

- **The data** — the derived tables the paper reports on: per-band features, membership
  stints, the spectrum classification and the timing analysis.
- **The analysis** — the R notebooks, run in order, each building on the tables the
  previous one wrote.
- **The Band Explorer** — a browser-based explorer for the membership records: search a
  band, see its line-up history and where it falls on the spectrum.

## Citing this work

A full citation with volume, pages and DOI will follow once the proceedings are published.

> Edward Abel, Andrew Goddard, Peter Smith, and John Hall. "When Is a Band a Sinking Ship:
> A Ship of Theseus Analysis of Membership Replacement and Band Survival." Anthology of
> Computers and the Humanities, forthcoming.

## Contact

Edward Abel, University of Southern Denmark — abel@sdu.dk
