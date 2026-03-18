# Slate

Slate is an open-source static site generator for creating beautiful, three-panel API documentation from Markdown files. Originally created by Robert Lord in 2013 at TripIt and maintained by the slatedocs organization, Slate is built on Ruby and the Middleman static site framework.

Slate renders documentation with a navigation sidebar on the left, API descriptions in the center panel, and code samples in the right panel. Documentation is written in Markdown with YAML frontmatter controlling page configuration, language tabs, included files, search, and meta tags.

- **GitHub:** https://github.com/slatedocs/slate
- **Live Demo:** https://slatedocs.github.io/slate/
- **Docker:** https://hub.docker.com/r/slatedocs/slate
- **Getting Started:** https://github.com/slatedocs/slate/wiki#getting-started

## API Artifacts

| Artifact | Type | Description |
|---|---|---|
| [slate-frontmatter-schema.json](json-schema/slate-frontmatter-schema.json) | JSON Schema | Schema for the YAML frontmatter configuration in Slate documentation pages (index.html.md) |
| [slate-context.jsonld](json-ld/slate-context.jsonld) | JSON-LD | Linked data context mapping Slate documentation entities to standard vocabularies |
