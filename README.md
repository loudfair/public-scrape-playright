# public-scrape-playright

Holding repo for design-system scrape tool guides. Each tool gets its own numbered folder with a Markdown guide and a dark-theme PDF.

> **Why this repo exists:** rather than creating a new repo every time a new design-scraping / design-token / site-cloning tool lands, each tool gets a folder here. When the collection stabilises it consolidates into one private repo.

---

## Guides

| # | Tool | Folder | Markdown | PDF (dark) |
|---|------|--------|----------|------------|
| 1 | **designlang** — extract any website's design system with one command (DTCG tokens, Tailwind v4, shadcn/ui, iOS/Android/Flutter/WordPress emitters, MCP server, Chrome extension) | [`design-1/`](./design-1/) | [designlang-how-to-use.md](./design-1/designlang-how-to-use.md) | [designlang-how-to-use.pdf](./design-1/designlang-how-to-use.pdf) |

---

## Adding a new guide

1. Create folder `design-N/` where `N` is the next integer.
2. Drop the `.md` guide and a dark-theme `.pdf` (same base filename) inside.
3. Add a new row to the **Guides** table above.
4. Commit and push. That is all.

## Folder naming convention

```
design-1/   First tool
design-2/   Second tool
design-3/   ...
```

Tool-specific files inside follow `<tool-name>-<doc-type>.<ext>`:

```
design-1/
├── designlang-how-to-use.md
└── designlang-how-to-use.pdf
```

---

## Why "scrape" + "playright"?

- **scrape** — all these tools scrape a live website's computed styles to produce design assets.
- **playright** — the browser automation engine most of them use (intentional spelling retained from initial naming).
