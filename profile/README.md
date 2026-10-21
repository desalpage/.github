desalpage is a governance substrate for recursive multi-agent work: agents delegating down a reporting structure, one bounded sprint at a time — budgets reserved before delegation, deferrals instead of silence.

Three mechanisms carry that discipline:

- **Reserve before you call.** Every model call is priced at its worst case and reserved against a balance that spans the whole delegation tree, *before* the provider is reached — a call that cannot be funded never runs.
- **Unfinished work is an outcome.** Work that cannot finish is a typed, auditable deferral, aggregated up the delegation tree — a run can end bounded, but never silently.
- **Governance at sprint boundaries.** A board cadence resolves structured asks between runs and folds them into the next run's configuration.

*desalpage* is the Alpine transhumance term for the planned descent of the herds when the high-pasture season ends: a bounded season, and an ending that is deliberate, complete, and never silent. The name is the design.

## Where to read

- **[Reserve before you call](https://desalpage.github.io/desalpage/blog/2026-10-21-reserve-before-you-call/)** — the first post: pre-call admission control over a recursive budget tree, and deferrals as a designed outcome.
- [Blog](https://desalpage.github.io/desalpage/blog/) — dated, citable documentation of the mechanisms, written for people and for AI agents · [RSS](https://desalpage.github.io/desalpage/rss.xml)
- [About](https://desalpage.github.io/desalpage/about/) — the name, the honesty discipline, and authorship disclosure.

## Where things live

Mechanisms are developed in a private prototype; this organization is the public release surface, and everything here arrives deliberately:

- [`desalpage/desalpage`](https://github.com/desalpage/desalpage) — the release monorepo: site, blog, and papers alongside code artifacts extracted one-way from the prototype, each with recorded provenance.
- [`papers/`](https://github.com/desalpage/desalpage/tree/main/papers) — preprints and artifact bundles; papers appear here when they are released, nothing pre-announced.
- [`packages/`](https://github.com/desalpage/desalpage/tree/main/packages) — extracted code artifacts; [`PROVENANCE.json`](https://github.com/desalpage/desalpage/blob/main/packages/PROVENANCE.json) is the definitive record of what exists.

## Status

The mechanisms are shipped and documented as shipped; the outcome evaluation (budgeted vs. unbudgeted runs at matched credits) is pending, and until it lands, public prose makes no quantitative claims. Prose on the public surface is drafted by AI agents under human direction and reviewed before publication — see [About](https://desalpage.github.io/desalpage/about/).

## License

Apache-2.0, copyright The desalpage Authors.
