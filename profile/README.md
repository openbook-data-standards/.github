## OpenBook Data Standards

Open, vendor-neutral data standards for markets. The contracts are open; every
implementation behind them stays the implementer's own.

Like GTFS for transit or OpenRTB for ad-tech: read the format once, consume
every publisher.

### The standards

- 📘 **OpenBook** — an open standard for sportsbook & gambling data: a
  reference model (sport → league → season → stage → fixture), a live wire
  (`odds/change`, `score/update`, `market/update`, `grade/create` as streamed
  diffs), and controlled vocabularies.
  [Specification](https://github.com/openbook-data-standards/openbook/blob/main/spec/openbook.md)
  · [Homepage](https://openbook-data-standards.github.io/openbook/)
  · [Schemas & vocabularies](https://github.com/openbook-data-standards/openbook)
  · [Decision log](https://github.com/openbook-data-standards/openbook/blob/main/docs/decisions.md)
- 🧭 **OpenVenue** — an open standard for vendor-agnostic routing of tokenized
  markets: a canonical market schema, an equivalence layer that resolves the
  same instrument across venues, and an all-in quote contract.
  [Specification](https://github.com/openbook-data-standards/openvenue/blob/main/spec/openvenue.md)

### What they share

- Neutral, namespaced canonical ids owned by the standard; vendor ids live on
  mapping records, never as canonical keys.
- Built on ISO 8601 / 4217, CLDR territories, Wikidata ids, schema.org field
  names and JSON Merge Patch — nothing reinvented.

### Get involved

Open a [proposal](https://github.com/openbook-data-standards/openbook/issues/new?labels=proposal)
or start a [discussion](https://github.com/openbook-data-standards/openbook/discussions).
The specifications are licensed **CC BY 4.0**; implementations may be fully proprietary.

> OpenBook: **v0.3.0-draft** — the model is settled; the wire may still change
> before 1.0. OpenVenue: **v0.0.1-draft** — early working draft.
