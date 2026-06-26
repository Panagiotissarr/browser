![animation](data:image/svg+xml;base64,PHN2ZyBmaWxsPSJub25lIiB2aWV3Qm94PSIwIDAgODAwIDIwMCIgeG1sbnM9Imh0dHA6Ly93d3cudzMub3JnLzIwMDAvc3ZnIj4KICA8Zm9yZWlnbk9iamVjdCB3aWR0aD0iMTAwJSIgaGVpZ2h0PSIxMDAlIj4KICAgIDxkaXYgeG1sbnM9Imh0dHA6Ly93d3cudzMub3JnLzE5OTkveGh0bWwiPgogICAgICA8c3R5bGU+CiAgICAgICAgLmNvbnRhaW5lciB7CiAgICAgICAgICAgIGJhY2tncm91bmQtY29sb3I6IHRyYW5zcGFyZW50OwogICAgICAgICAgICBkaXNwbGF5OiBmbGV4OwogICAgICAgICAgICBqdXN0aWZ5LWNvbnRlbnQ6IGNlbnRlcjsKICAgICAgICAgICAgYWxpZ24taXRlbXM6IGNlbnRlcjsKICAgICAgICAgICAgaGVpZ2h0OiAyMDBweDsKICAgICAgICAgICAgbWFyZ2luOiAwOwogICAgICAgIH0KICAgICAgICAubGF5ZXJlZC1zaGFkb3ctdGV4dCB7CiAgICAgICAgICAgIGNvbG9yOiAjZmZmOwogICAgICAgICAgICBmb250LXdlaWdodDogYm9sZDsKICAgICAgICAgICAgZm9udC1mYW1pbHk6ICJDb21pYyBTYW5zIE1TIiwgY3Vyc2l2ZSwgc2Fucy1zZXJpZjsKICAgICAgICAgICAgZm9udC1zaXplOiA4N3B4OwogICAgICAgICAgICB0ZXh0LWFsaWduOiBjZW50ZXI7CiAgICAgICAgICAgIGFuaW1hdGlvbjogc21vb3RoUHVycGxlU3RhY2sgMXMgY3ViaWMtYmV6aWVyKDAsIDAsIDEsIDEpIGluZmluaXRlIGFsdGVybmF0ZTsKICAgICAgICB9CgogICAgICAgIEBrZXlmcmFtZXMgc21vb3RoUHVycGxlU3RhY2sgewogICAgICAgICAgICAwJSB7CiAgICAgICAgICAgICAgICB0ZXh0LXNoYWRvdzoKICAgICAgICAgICAgICAgICAgICA1cHggNXB4IDBweCAjMDA3NWM5LAogICAgICAgICAgICAgICAgICAgIDcuNXB4IDcuNXB4IDBweCAjMDAwMGU2LAogICAgICAgICAgICAgICAgICAgIDEwcHggMTBweCAwcHggIzBiMDA3MDsKICAgICAgICAgICAgfQogICAgICAgICAgICA1MCUgewogICAgICAgICAgICAgICAgdGV4dC1zaGFkb3c6CiAgICAgICAgICAgICAgICAgICAgMHB4IDVweCAwcHggIzAwNzVjOSwKICAgICAgICAgICAgICAgICAgICAwcHggNy41cHggMHB4ICMwMDAwZTYsCiAgICAgICAgICAgICAgICAgICAgMHB4IDEwcHggMHB4ICMwYjAwNzA7CiAgICAgICAgICAgIH0KICAgICAgICAgICAgMTAwJSB7CiAgICAgICAgICAgICAgICB0ZXh0LXNoYWRvdzoKICAgICAgICAgICAgICAgICAgICAtNXB4IDVweCAwcHggIzAwNzVjOSwKICAgICAgICAgICAgICAgICAgICAtNy41cHggNy41cHggMHB4ICMwMDAwZTYsCiAgICAgICAgICAgICAgICAgICAgLTEwcHggMTBweCAwcHggIzBiMDA3MDsKICAgICAgICAgICAgfQogICAgICAgIH0KICAgICAgPC9zdHlsZT4KICAgICAgPGRpdiBjbGFzcz0iY29udGFpbmVyIj4KICAgICAgICA8aDEgY2xhc3M9ImxheWVyZWQtc2hhZG93LXRleHQiPkFsdGlvciBCcm93c2VyPC9oMT4KICAgICAgPC9kaXY+CiAgICA8L2Rpdj4KICA8L2ZvcmVpZ25PYmplY3Q+Cjwvc3ZnPg==)

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
