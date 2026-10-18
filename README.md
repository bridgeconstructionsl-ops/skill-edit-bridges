# skill-edit-bridges

## Skills

| Skill | Source | What it does |
|---|---|---|
| `convert-documents-to-markdown` | [firecrawl/anydoc](https://github.com/firecrawl/anydoc/tree/main/skills/convert-documents-to-markdown) at `ab0e4c4` | Converts Word, PowerPoint, Excel, OpenDocument, RTF, EPUB, CSV and PDF files to Markdown with `npx -y @firecrawl/anydoc` (Node 20+) |

`convert-documents-to-markdown` is vendored unchanged with its own MIT `LICENSE`; update it by re-copying from upstream rather than editing it here. It runs the latest `@firecrawl/anydoc` release from npm, unpinned. Scanned PDFs need `--ocr hosted`, which uploads the file to Firecrawl, so ask before using it.

Install for all projects:

```bash
mkdir -p ~/.claude/skills && cp -R .claude/skills/convert-documents-to-markdown ~/.claude/skills/
```
