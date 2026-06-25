# Contributing

1. Add your resource to `data/image-prompts.json` or `data/video-prompts.json`
2. Follow the existing entry schema
3. Submit a PR

```json
{
  "id": "kebab-case-name",
  "name": "Display Name",
  "url": "https://github.com/owner/repo",
  "sourceType": "github",
  "stars": 0,
  "description": "One-line description",
  "models": ["model-name"],
  "format": "text",
  "lang": "en"
}
```

- `id`: kebab-case, unique
- `sourceType`: `"github"` or `"web"`
- `models`: use lowercase, e.g. `gpt-image`, `nanobanana`, `midjourney`, `flux`, `seedream`, `stable-diffusion`, `sora`, `runway`, `pika`, `kling`, `veo`
- `format`: `"text"` (plain text prompts), `"json"` (structured JSON), `"structured"` (other structured formats)

PRs welcome!
