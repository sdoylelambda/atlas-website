# Atlas Website

The landing page and portfolio site for **Atlas** — a free, local-first AI assistant.

This repo contains the marketing/download site only. For the actual application code, see the links below.

---

## Related repos

| Repo | What it is |
|------|------------|
| [A.T.L.A.S.](https://github.com/sdoylelambda/A.T.L.A.S.) | Core desktop application — Python, local LLM routing, voice I/O, GUI |
| [A.T.L.A.S.-mobile](https://github.com/sdoylelambda/A.T.L.A.S.-mobile) | Android/Flutter mobile client — remote control for the desktop app |

---

## What's in this repo

- `index.html` — homepage: hero, video demos, screenshots, download links
- `features.html` — architecture breakdown, orb states, sample commands, privacy stance, platform support
- `assets/` — screenshots and images used across the site

Plain HTML/CSS, no build step or framework — open either file directly or serve via GitHub Pages.

---

## Downloads

Built binaries (Linux, Android) are published under [Releases](https://github.com/sdoylelambda/atlas-website/releases) rather than committed to this repo. Windows and macOS builds are planned.

---

## Local development

No build tooling required — edit the HTML/CSS directly and open in a browser, or serve locally:

```bash
python3 -m http.server
```

Then visit `http://localhost:8000`.

---

## License

MIT — same as the main Atlas project.
