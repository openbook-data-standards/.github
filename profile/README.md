## OpenBook Data Standards

**An open, vendor-neutral standard for sportsbook & gambling data** — a
reference model, a live wire, and controlled vocabularies. One format any
sportsbook or feed emits odds in; read it once, consume every publisher.

Like GTFS for transit or OpenRTB for ad-tech: the data contract is open, and
every implementation behind it stays the implementer's own.

### Start here

- 📘 **Specification** — https://github.com/openbook-data-standards/openbook/blob/main/spec/openbook.md
- 🌐 **Homepage** — https://openbook-data-standards.github.io/openbook/
- 🧩 **Schemas & vocabularies** — https://github.com/openbook-data-standards/openbook
- 🗒️ **Why each decision** — [the decision log](https://github.com/openbook-data-standards/openbook/blob/main/docs/decisions.md)

### What it covers

- **Reference tier** — sport → league → season → stage → fixture, participants
  (teams & individuals), and shared vocabularies for market types, segments and sides.
- **Live tier** — `odds/change`, `score/update`, `market/update`, `grade/create`
  as streamed diffs, fixture-first, with a monotonic sequence cursor.
- Built on ISO 8601 / 4217, CLDR territories, Wikidata ids, schema.org field
  names and JSON Merge Patch — nothing reinvented.

### Get involved

Open a [proposal](https://github.com/openbook-data-standards/openbook/issues/new?labels=proposal)
or start a [discussion](https://github.com/openbook-data-standards/openbook/discussions).
The specification is licensed **CC BY 4.0**; implementations may be fully proprietary.

> Status: **v0.3.0-draft** — the model is settled; the wire may still change before 1.0.
