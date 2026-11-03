# DeployCo site

A blank white page with the official DeployCo logo. No chat interface or sample content.

## Source

- `dist/index.html` — blank page and logo header
- `dist/style.css` — minimal responsive styling
- `dist/logo.svg` — DeployCo wordmark
- `dist/mark.svg` — favicon
- `.openai/hosting.json` — existing ChatGPT Sites project and static directory

## Local preview

No build or dependencies are needed. From the repository root:

```sh
python3 -m http.server 4173 --directory dist
```

Open http://localhost:4173.

## Production

https://deployco-chat-workspace.deploy.chatgpt.site

Production access is managed in ChatGPT Sites. This GitHub repository is a source copy; GitHub commits do not automatically deploy to the live site.
