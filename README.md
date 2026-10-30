# IQM Quantum Computers

<!-- API-EVANGELIST-PROVENANCE:BEGIN -->
> ### About this repository
>
> **This is not our API.** This repository is an independent, third-party profile of a company's
> **publicly available** API surface, maintained by [API Evangelist](https://apievangelist.com).
> API Evangelist does not operate, host, resell, or support this company's APIs, and is not
> affiliated with or endorsed by the company unless stated on the profile.
>
> **Where the information came from.** Everything here is assembled from material a member of the
> public can reach with a browser and no credentials — the company's own website, developer portal
> and documentation, the specifications it publishes for public use (OpenAPI, AsyncAPI, JSON Schema,
> `apis.json`, `llms.txt` and similar), its public repositories, and its public status, pricing and
> changelog pages. **Nothing here is obtained by breaching a system, defeating an access control, or
> using credentials of any kind.**
>
> **The rating is an independent assessment.** The Kin Score and Agent Readiness rating are
> independently calculated scores of a company's *public* API artifacts, produced by API Evangelist
> against a published rubric. They are not certifications, endorsements, security assessments, or
> audits, and they score published artifacts — not the quality, safety, or security of the software.
>
> **Corrections, re-scores, and removal are free.** No partnership, contract, or purchase is
> required, and you do not need to justify the request.
>
> - **Something wrong?** Open an issue on this repository, or email
>   [info@apievangelist.com](mailto:info@apievangelist.com).
> - **Published something new?** Ask for a re-score and we will re-run the rating.
> - **Want the listing taken down?** Say so and we will honor it. The profile is reduced to your
>   company name, a factual description, and a link to your own site, and the company is recorded as
>   **unrated** — never scored zero for having asked.
>
> **Response times.** Acknowledgement within **one business day**; removal or restriction within
> **two business days**; corrections and re-scores within **five business days**.
>
> **Not from the company, and here with a question?** You are welcome here — we would rather be the
> front line and point you the right way than have a good report go nowhere. What this repository
> can answer is narrow, though, so it is worth knowing who you are actually looking for:
>
> - **A question about how the API works, an account, billing, or a bug in the service** — that is
>   the company's own support, not us. We profile this API; we do not operate it and cannot see
>   your account.
> - **A bug in an open-source project we only catalog** — file it on that project's own repository.
>   This has happened with a real and correct bug report that reached us instead of the people who
>   could fix it, which helped nobody.
> - **Anything about this listing itself** — the description, the tags, the rating, a missing or
>   wrong artifact — is ours. Open an issue here.
> - **Not sure, or something general about API Evangelist or APIs.io** — open an issue on the
>   [APIs.io Inbox](https://github.com/api-search/inbox) and we will route it.
>
> **This repository contains no software, and we will never ask you to download anything.** There is
> no build, release, installer, or binary here — only text and machine-readable API descriptions, so
> there is nothing here that can be "corrupt" or need "repairing". Any issue, comment, or email
> claiming otherwise and offering a download link is not from us and is hostile. Do not follow the
> link; it is a lure. Report it to GitHub and, if you like, tell us at
> [info@apievangelist.com](mailto:info@apievangelist.com) so we can take it down.
>
> **On a security or compliance team?** Email
> [info@apievangelist.com](mailto:info@apievangelist.com) with *security* in the subject line and
> you will get a person, not a form. We will tell you exactly which public URLs this profile was
> built from so your team can see the same surface we did, and we will take the listing down on
> request while you work through it.
>
> Full detail: **[Where this data comes from](https://apievangelist.com/about/where-our-data-comes-from)**
<!-- API-EVANGELIST-PROVENANCE:END -->

IQM Quantum Computers (IQM Finland Oy) builds superconducting quantum computers and sells access to them, both as on-premises systems and as a cloud service. Its developer surface is IQM Resonance, a quantum cloud platform at resonance.iqm.tech whose REST API accepts circuits, queues them against a named QPU, and returns measurement results — billed in QPU seconds rather than API calls. Access is through a bearer API token generated from the Resonance dashboard, and the practical client contract is IQM's Apache-2.0 Python stack (iqm-client, with Qiskit, Cirq and Qrisp adapters) rather than a published OpenAPI, which IQM does not ship. IQM does publish 14 first-party Protobuf message contracts defining the Station Control wire format, a dated changelog with explicit breaking-change notices, and a free Starter tier with a monthly credit allowance.

**Areas:** Quantum Computing · Quantum Cloud · High Performance Computing · Research · Scientific Computing · Developer Tools · Protobuf · Hardware · Finland · Deep Tech

## IQM Quantum Computers on APIs.io

Everything profiled for IQM Quantum Computers is published on APIs.io rather than in this repository. Start at the provider page — **[apis.io/providers/iqm-quantum-computers/](https://apis.io/providers/iqm-quantum-computers/)** — or go straight to one of the APIs or properties below.

### APIs (1)

- [IQM Resonance API](https://apis.io/apis/iqm-quantum-computers/iqm-quantum-computers-resonance/) — The REST API behind IQM Resonance, IQM's quantum cloud service. It lists the quantum computers available on a server, reports their health and calibration…

### Published properties

Each property below is a page on APIs.io carrying the machine-readable artifact and what it says.

#### MCP servers (1)

Model Context Protocol servers that expose the API to agents.

- [iqm-resonance](https://apis.io/servers/iqm-quantum-computers/iqm-resonance/)

#### Security (2)

Authentication, trust centre, and vulnerability disclosure.

- [Iqm Quantum Computers Authentication](https://apis.io/security/iqm-quantum-computers/iqm-quantum-computers-authentication/)
- [Iqm Quantum Computers Domain Security](https://apis.io/security/iqm-quantum-computers/iqm-quantum-computers-domain-security/)

#### Plans and pricing (1)

Published plans, tiers and prices.

- [Iqm Quantum Computers Plans Pricing](https://apis.io/plans/iqm-quantum-computers/iqm-quantum-computers-plans-pricing/)

#### Rate limits (1)

Published request limits.

- [Iqm Quantum Computers Rate Limits](https://apis.io/rate-limits/iqm-quantum-computers/iqm-quantum-computers-rate-limits/)

## Where to find this API

Links to the company's own pages. This repository publishes no copy of their specifications — the canonical document is theirs and lives at the URLs below.

- [Website](https://iqm.tech/)
- [Documentation](https://docs.iqm.tech/iqm-client/)
- [Getting started](https://docs.iqm.tech/iqm-client/user_guide_qiskit.html)
- [API reference](https://docs.iqm.tech/iqm-client/API.html)
- [Pricing](https://iqm.tech/products/iqm-resonance/)
- [Sign up](https://resonance.iqm.tech/sign-up)
- [Support](https://iqm.tech/contact/)
- [Blog](https://iqm.tech/blog/)
- [Privacy policy](https://iqm.tech/privacy-policy/)
- [GitHub](https://github.com/iqm-finland)

## API Evangelist rating

**Kin Score 44.5** — developing · rubric 0.25.0 · scored 2026-10-23

| Facet | Score |
|---|---|
| Discoverability | 66.1 |
| Contract quality | 24.0 |
| Contract governance | 4.5 |
| Operational transparency | 23.7 |
| Developer ergonomics | 71.4 |
| Access clarity | 65.8 |

**Agent readiness 18.7** — agent-aware

| Agent-readiness dimension | Result |
|---|---|
| Spec Presence | yes |
| Agentic Access | — |
| Reversibility Documented | — |
| MCP Server | — |
| Auth Clarity | bearer (partial credit) |
| Idempotency | — |
| Error Semantics | derived (partial credit) |
| OpenAPI Examples | — |
| Rate Limit Signal | documented (partial credit) |
| Event Surface Described | — |
| Agent Skills | — |
| Well Known Catalog | — |
| Consent Identity | — |
| Agent Card | — |
| Dry Run Mode | — |
| Delegated Identity | — |
| Protected Resource Metadata | — |
| Dynamic Client Registration | — |
| Agentic Commerce | — |
| Pagination Ratio | na |
| Operation Distinctiveness | na |

**Regulatory alignment 20.6** — Horizontal (data, software, accessibility, platform)

The rubric is published at [github.com/api-evangelist/kin-score](https://github.com/api-evangelist/kin-score). The per-check breakdown behind these numbers — which checks were earned, partial or missed — along with score history and how this provider compares to its peers, is available at [apis.io/providers/iqm-quantum-computers/](https://apis.io/providers/iqm-quantum-computers/).

## How this profile is made

API Evangelist profiles a company's public API surface the way a developer would find it: the website, developer portal and documentation, the specifications it publishes, its public repositories, and its pricing, status and changelog pages. From that it derives the properties above — contracts split per API, workflows, schemas, collections, governance rules, plans and rate limits — and scores them against the published [Kin Score rubric](https://github.com/api-evangelist/kin-score).

The artifacts are published on [APIs.io](https://apis.io), not in this repository. This repository is the public record for IQM Quantum Computers: the place to say something is wrong, missing or out of date, and to ask for a re-score or a removal.

## Open an issue

- **Something about this listing** — a wrong description, a missing API, a stale artifact or a question about the rating: [open an issue on this repository](https://github.com/api-evangelist/iqm-quantum-computers/issues/new).
- **A new API, or one that is not in the catalog yet** — [submit it on APIs.io](https://apis.io/add/).
- **Anything else** — [the APIs.io inbox](https://github.com/api-search/inbox/issues/new) or [info@apievangelist.com](mailto:info@apievangelist.com).
