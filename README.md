# hugolify-theme-render-hook

## Install

Edit `config/_default/module.yaml` to install the `hugolify-theme-render-hook` module:

```yml
imports:
  - path: github.com/hugolify/hugolify-theme-render-hook
  - path: github.com/hugolify/hugolify-theme-icons # optional for icons
  - path: github.com/hugolify/hugolify-theme/v2 # required
```

## Anchored headings (render-heading)

Adds a per-heading anchor link (#id) to Markdown headings, with an optional
Lucide icon via the `{icon="name"}` attribute.

Enable it in `config/_default/params.yaml`:

```yaml
headings:
  anchor: true
```

## Documentation

https://www.hugolify.io/docs/

## Licensing

Hugolify is free for personal or commercial projects (MIT license)