![animation](data:image/svg+xml;base64,PHN2ZyBmaWxsPSJub25lIiB2aWV3Qm94PSIwIDAgODAwIDIwMCIgeG1sbnM9Imh0dHA6Ly93d3cudzMub3JnLzIwMDAvc3ZnIj48Zm9yZWlnbk9iamVjdCB3aWR0aD0iMTAwJSIgaGVpZ2h0PSIxMDAlIj48ZGl2IHhtbG5zPSJodHRwOi8vd3d3LnczLm9yZy8xOTk5L3hodG1sIj48c3R5bGU+QGtleWZyYW1lcyBzbW9vdGhQdXJwbGVTdGFja3swJXt0ZXh0LXNoYWRvdzo1cHggNXB4IDAjMDA3NWM5LDcuNXB4IDcuNXB4IDAjMDAwMGU2LDEwcHggMTBweCAwIzBiMDA3MH01MCV7dGV4dC1zaGFkb3c6MCA1cHggMCMwMDc1YzksMCA3LjVweCAwIzAwMDBlNiwwIDEwcHggMCMwYjAwNzB9dG97dGV4dC1zaGFkb3c6LTVweCA1cHggMCMwMDc1YzksLTcuNXB4IDcuNXB4IDAjMDAwMGU2LC0xMHB4IDEwcHggMCMwYjAwNzB9fS5jb250YWluZXJ7YmFja2dyb3VuZC1jb2xvcjp0cmFuc3BhcmVudDtkaXNwbGF5OmZsZXg7anVzdGlmeS1jb250ZW50OmNlbnRlcjthbGlnbi1pdGVtczpjZW50ZXI7aGVpZ2h0OjIwMHB4O21hcmdpbjowfS5sYXllcmVkLXNoYWRvdy10ZXh0e2NvbG9yOiNmZmY7Zm9udC13ZWlnaHQ6NzAwO2ZvbnQtZmFtaWx5OiZxdW90O0NvbWljIFNhbnMgTVMmcXVvdDssY3Vyc2l2ZSxzYW5zLXNlcmlmO2ZvbnQtc2l6ZTo4N3B4O3RleHQtYWxpZ246Y2VudGVyO2FuaW1hdGlvbjpzbW9vdGhQdXJwbGVTdGFjayAxcyBjdWJpYy1iZXppZXIoMCwwLDEsMSkgaW5maW5pdGUgYWx0ZXJuYXRlfTwvc3R5bGU+PGRpdiBjbGFzcz0iY29udGFpbmVyIj48aDEgY2xhc3M9ImxheWVyZWQtc2hhZG93LXRleHQiPkFsdGlvciBCcm93c2VyPC9oMT48L2Rpdj48L2Rpdj48L2ZvcmVpZ25PYmplY3Q+PC9zdmc+)

<h1> Altior Browser </h1>
<h2> A simplictic proxy browser </h2>

I love simplicity. That's why I built Altior Browser; a super simple self-hosted web proxy with a full tabbed-browser interface, using
[Scramjet](https://github.com/MercuryWorkshop/scramjet). It serves a single-page
"browser" UI that renders proxied sites in real tabs, complete with bookmarks, search suggestions, and a games sidebar.

<br>

## Demo
### [https://altior-browser.onrender.com](https://altior-browser.onrender.com)

<br>

## Features

- **Tabbed browsing** — open, close, pin, reorder (drag), and duplicate tabs.
  Each tab is its own isolated Scramjet frame.
- **Search suggestions** — live Google autocomplete in both the omnibox and the
  new-tab page, fetched same-origin through the proxy.
- **Bookmarks bar** — add, edit, and organize bookmarks into folders.
- **Games sidebar** — a one-click panel (icon to the right of the URL bar) with a
  curated list of game sites.
- **Proxied favicons** — site icons load through the proxy so they aren't blocked
  by the page's cross-origin isolation policy.
- **Collapsible chrome** — hide the whole toolbar/tab strip for a fullscreen view.

<br>

## Run Localy

### Requirements

- **[Node.js](https://nodejs.org/en/download/current)** 18+ (the project targets `node >= 16`)
- **[pnpm](https://pnpm.io/)** (the repo pins `pnpm@10` via `packageManager`)

<br>

```bash
git clone https://github.com/ltorl/altior-browser.git && cd altior-browser
```

```bash
pnpm install
```

```bash
pnpm start
```
<br>

### Restart Later:

```bash
cd altior-browser && pnpm start
```

<br>

## Server Deployments:

| Service | Button |
| :--- | :--- |
| **Render** | [![Deploy to Render](https://render.com/images/deploy-to-render-button.svg)](https://dashboard.render.com/web/new?repo=https%3A%2F%2Fgithub.com%2Fltorl%2Faltior-browser) |
| **Railway** | [![Deploy on Railway](https://railway.app/button.svg)](https://railway.app/new/template?template=https://github.com/ltorl/altior-browser) |
| **Replit** | [![Run on Replit](https://replit.com/badge/github/ltorl/altior-browser)](https://replit.com/github/ltorl/altior-browser) |
| **Glitch** | [![Remix on Glitch](https://raw.githubusercontent.com/BinBashBanana/deploy-buttons/refs/heads/main/buttons/remade/glitch.svg)](https://glitch.com/edit/#!/import/github/ltorl/altior-browser) |

<br>

## Dependencies used:

- [@mercuryworkshop](https://github.com/MercuryWorkshop)/[scramjet](https://github.com/MercuryWorkshop/scramjet)
- [@mercuryworkshop](https://github.com/MercuryWorkshop)/[bare-mux](https://github.com/MercuryWorkshop/bare-mux)
- [@mercuryworkshop](https://github.com/MercuryWorkshop)/[libcurl-transport](https://github.com/MercuryWorkshop/libcurl-transport)
- [@mercuryworkshop](https://github.com/MercuryWorkshop)/[wisp-js](https://github.com/MercuryWorkshop/wisp-js)
