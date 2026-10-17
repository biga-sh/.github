<p align="center">
  <a href="https://website-vw4l.vercel.app/">
    <picture>
      <source media="(prefers-color-scheme: dark)" srcset="https://website-vw4l.vercel.app/brand/biga-logo-light.svg">
      <img src="https://website-vw4l.vercel.app/brand/biga-logo.svg" width="180" alt="biga">
    </picture>
  </a>
</p>

<h1 align="center">Stream your saves, not your screen</h1>

<p align="center">
  Your codebase. A live link. Nothing to install for viewers.
</p>

<p align="center">
  <a href="https://github.com/biga-sh/cli/releases/latest"><img src="https://img.shields.io/github/v/release/biga-sh/cli?style=flat-square&labelColor=0c0d10&color=63e197&label=cli" alt="Latest CLI release"></a>
  <a href="https://github.com/biga-sh/cli/blob/main/LICENSE"><img src="https://img.shields.io/badge/license-MIT-63e197?style=flat-square&labelColor=0c0d10" alt="MIT license"></a>
</p>

<p align="center">
  <a href="https://website-vw4l.vercel.app/">Website</a> ·
  <a href="https://website-vw4l.vercel.app/docs">Documentation</a> ·
  <a href="https://website-vw4l.vercel.app/#how-it-works">How it works</a> ·
  <a href="https://website-vw4l.vercel.app/docs/self-hosting">Self-hosting</a>
</p>

---

Screen sharing sends pixels. biga sends the files themselves.

Run one command in your project, share the link, and let anyone inspect your source code in their browser as you work. They can navigate files, search, read syntax-highlighted code and step through checkpoints without cloning your repository or creating an account.

## Get started

```bash
curl -fsSL https://raw.githubusercontent.com/biga-sh/cli/main/install.sh | sh
biga start
```

That's it. Share the link and keep coding. Windows, Go and other install options are in the [quickstart](https://website-vw4l.vercel.app/docs/quickstart).

## Made for the moments between commits

| | |
|:---|:---|
| **Pairing across timezones** | Let someone inspect the code while you make changes. |
| **Code reviews** | Share an in-progress implementation without asking someone to clone it. |
| **Teaching and mentoring** | Walk through a real codebase without setup on the viewer's machine. |
| **Building in public** | Give people a live view of your work, not a recording of your screen. |

## Small tool, thoughtful details

- **Only changed files travel.** Content hashes avoid sending unchanged files again.
- **Every checkpoint stays in the session.** Step back through changes and inspect file diffs.
- **Rejoin the same session.** Restart the CLI and keep sharing the same link.
- **Read-only for viewers.** A link lets people watch, nothing more.
- **Privacy-aware file filtering.** Sensitive paths and ignored files stay out of the shared tree.

Curious what happens after `biga start`? **[Explore how biga works →](https://website-vw4l.vercel.app/#how-it-works)**

## Documentation

- [Quickstart](https://website-vw4l.vercel.app/docs/quickstart)
- [What gets shared](https://website-vw4l.vercel.app/docs/what-gets-shared)
- [Architecture](https://website-vw4l.vercel.app/docs/architecture)
- [Self-hosting](https://website-vw4l.vercel.app/docs/self-hosting)
- [Brand](https://website-vw4l.vercel.app/brand)

## Repositories

| Repository | What it is |
| --- | --- |
| [cli](https://github.com/biga-sh/cli) | The `biga` command. Watches a folder and streams every save. |
| [server](https://github.com/biga-sh/server) | The Go API. Stores sessions and streams updates to viewers. |
| [website](https://github.com/biga-sh/website) | The site, the live viewer and the documentation. |
| [docker](https://github.com/biga-sh/docker) | Self-hosting: the whole stack with Docker Compose. |

## Contributing

Bug reports, focused fixes and pull requests are welcome. Read the [contributing guide](https://github.com/biga-sh/.github/blob/main/CONTRIBUTING.md) before you start, and report vulnerabilities privately as described in the [security policy](https://github.com/biga-sh/.github/blob/main/SECURITY.md), not in a public issue.

## License

biga is MIT licensed.

---

<p align="center">
  <sub><a href="https://website-vw4l.vercel.app/">biga</a> · Made for people who teach, pair and build in public.</sub>
</p>
