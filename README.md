# Slate

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
