# Slate

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

Slate is an open-source static site generator for creating beautiful, three-panel API documentation from Markdown files. Originally created by Robert Lord in 2013 at TripIt and maintained by the slatedocs organization, Slate is built on Ruby and the Middleman static site framework.

Slate renders documentation with a navigation sidebar on the left, API descriptions in the center panel, and code samples in the right panel. Documentation is written in Markdown with YAML frontmatter controlling page configuration, language tabs, included files, search, and meta tags.

## Links

- [GitHub](https://github.com/slatedocs/slate)
- [Live Demo](https://slatedocs.github.io/slate/)
- [Docker Image](https://hub.docker.com/r/slatedocs/slate)
- [Getting Started](https://github.com/slatedocs/slate/wiki#getting-started)
- [Using Slate Natively](https://github.com/slatedocs/slate/wiki/Using-Slate-Natively)
- [Using Slate in Docker](https://github.com/slatedocs/slate/wiki/Using-Slate-in-Docker)
- [Slate in the Wild](https://github.com/slatedocs/slate/wiki/Slate-in-the-Wild)
- [Changelog](https://github.com/slatedocs/slate/blob/main/CHANGELOG.md)
- [Discussions](https://github.com/slatedocs/slate/discussions)
- [License (Apache 2.0)](https://github.com/slatedocs/slate/blob/main/LICENSE)

## Artifacts

### JSON Schema

| File | Description |
|---|---|
| [json-schema/slate-frontmatter-schema.json](json-schema/slate-frontmatter-schema.json) | JSON Schema for the YAML frontmatter configuration in Slate documentation pages (index.html.md) |

### JSON Structure

| File | Description |
|---|---|
| [json-structure/slate-frontmatter-structure.json](json-structure/slate-frontmatter-structure.json) | Field-level structure documentation for all Slate frontmatter configuration options |

### Linked Data

| File | Description |
|---|---|
| [json-ld/slate-context.jsonld](json-ld/slate-context.jsonld) | JSON-LD context mapping Slate documentation entities to schema.org and Dublin Core vocabularies |

### Examples

| File | Description |
|---|---|
| [examples/slate-frontmatter-example.json](examples/slate-frontmatter-example.json) | Example frontmatter configuration with all options demonstrated |

### Vocabulary

| File | Description |
|---|---|
| [vocabulary/slate-vocabulary.yml](vocabulary/slate-vocabulary.yml) | Domain vocabulary covering Slate's three-panel layout, Middleman build system, frontmatter configuration, Rouge syntax highlighting, and deployment |

## GitHub Organization

The [slatedocs](https://github.com/slatedocs) organization maintains the official Slate repository with 36,000+ stars. Notable repos:

| Repo | Description |
|---|---|
| [slatedocs/slate](https://github.com/slatedocs/slate) | Main Slate documentation generator |
| [slatedocs/img](https://github.com/slatedocs/img) | Image assets for Slate documentation |

## Maintainers

- **Kin Lane** - kin@apievangelist.com
