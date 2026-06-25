# awesome-prompt

[![Awesome](https://awesome.re/badge.svg)](https://awesome.re)
[![MIT License](https://img.shields.io/badge/License-MIT-green.svg)](LICENSE)
[![PRs Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen.svg)](CONTRIBUTING.md)

> Curated index of open-source AI image & video prompt resources.
> AI 文生图/文生视频 提示词资源聚合索引 — 给 Agent 看的结构化清单。

**Target audience**: AI agents & developers who need to find, query, or aggregate prompt datasets programmatically.

## Structured Data

Machine-readable indexes:

| File | Description |
|------|-------------|
| `data/image-prompts.json` | AI image generation prompt resources |
| `data/video-prompts.json` | AI video generation prompt resources |

Each entry in `data/*.json` follows:

```json
{
  "id": "unique-slug",
  "name": "Resource Name",
  "url": "https://...",
  "sourceType": "github" | "web",
  "stars": 0,
  "description": "Short description",
  "models": ["gpt-image", "nanobanana", "midjourney", ...],
  "format": "text" | "json" | "structured",
  "lang": "en" | "zh" | "multi",
  "updatedAt": "2026-06-25"
}
```

## Contribute

See [CONTRIBUTING.md](CONTRIBUTING.md).

## License

MIT
