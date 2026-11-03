## OpenBook Data Standards

Vendor-neutral data contracts for sportsbook, exchange and tokenized markets,
with supporting tools and experimental models. The contracts are public;
implementations, provider adapters, models, strategies and licensed data can stay
private.

### Start with your goal

**[Ecosystem onboarding guide](https://github.com/openbook-data-standards/openbook/blob/main/docs/onboarding.md)**
· **[Project catalog and readiness](https://github.com/openbook-data-standards/openbook/blob/main/docs/ecosystem.md)**
· **[Install agent skills](https://github.com/openbook-data-standards/openbook/blob/main/docs/agent-skills.md)**
· **[Add a project or workflow](https://github.com/openbook-data-standards/openbook/blob/main/docs/extending-ecosystem.md)**

The catalog is the canonical inventory for observed versions, licenses,
prerequisites, distribution and named blockers. Do not assume a draft has a
published package or that sibling projects are automatically interoperable.
Synthetic onboarding does not require a provider account, database or cloud.

### Standards and profiles

| Project | What it describes |
| --- | --- |
| [OpenBook](https://github.com/openbook-data-standards/openbook) | Sportsbook reference catalog, fixtures, markets, odds, scores, grades and live change envelopes. |
| [OpenBook Betting](https://github.com/openbook-data-standards/openbook-betting) | Venue coverage and bet-order lifecycle; a draft profile with its own envelope compatibility boundary. |
| [OpenExchange](https://github.com/openbook-data-standards/openexchange) | Exchange venues, market state, runners, back/lay depth and fees. |
| [OpenVenue](https://github.com/openbook-data-standards/openvenue) | Tokenized market identity, equivalence, order books and all-in quote contracts. |

These contracts are drafts, not hosted feeds, routers or execution services.
Specification material is CC BY 4.0; consult each repository's license and
normative source before implementing.

### Implementation tools

| Project | First use |
| --- | --- |
| [openbook-starter](https://github.com/openbook-data-standards/openbook-starter) | Scaffold publisher/discovery documents, not a complete server. |
| [openbook-translate](https://github.com/openbook-data-standards/openbook-translate) | Build separately maintained adapters with mapping, quarantine, gaps and envelope helpers. |
| [openbook-js](https://github.com/openbook-data-standards/openbook-js) | Consume snapshots/streams, cache documents, optionally derive prices or bind React. Check distribution readiness before installing. |

Code licensing and vendored specification licensing differ; keep attribution
and consult each project's LICENSE/NOTICE. Private provider adapters and live
credentials are not bundled.

### Experimental models

- [OpenProb](https://github.com/openbook-data-standards/openprob): Apache-2.0
  provider-neutral forecasting and evaluation tools with synthetic examples.
- [OpenTrack](https://github.com/openbook-data-standards/opentrack): publicly
  readable horse-racing models. **License pending**: public visibility does not
  grant open-source reuse/distribution rights.

These standalone models do not claim conformance to OpenBook or automatic
interoperability with other family projects.

### Agents and contributors

The OpenBook repository contains portable SKILL.md workflows for ecosystem
orientation, publishing, translation, consumption, market contracts, forecasting,
racing and contribution. See the installation guide for agent-specific setup and
acceptance checks. Skills supply guidance, not credentials, MCP services,
permission to execute orders, or a claim that every agent has been certified.

To extend the ecosystem, add reviewed evidence to the shared catalog and a
synthetic first-success journey using the linked extension templates. The catalog
and skill reference are generated together to reduce drift.

Read [contribution guidance](https://github.com/openbook-data-standards/openbook/blob/main/CONTRIBUTING.md)
and the target repository's own agent rules before proposing a change. Existing
field names, identities and contracts are not changed by onboarding work.

[OpenBook homepage](https://openbook-data-standards.github.io/openbook/)
· [Specification](https://github.com/openbook-data-standards/openbook/blob/main/spec/openbook.md)
· [Decision log](https://github.com/openbook-data-standards/openbook/blob/main/docs/decisions.md)
