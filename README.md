![animation](data:image/svg+xml,%3Csvg%20fill%3D%22none%22%20viewBox%3D%220%200%20800%20200%22%20xmlns%3D%22http%3A%2F%2Fwww.w3.org%2F2000%2Fsvg%22%3E%3CforeignObject%20width%3D%22100%25%22%20height%3D%22100%25%22%3E%3Cdiv%20xmlns%3D%22http%3A%2F%2Fwww.w3.org%2F1999%2Fxhtml%22%3E%3Cstyle%3E%20%20%20%20%20%20%20%20.container%20%7B%20%20%20%20%20%20%20%20%20%20%20%20background-color%3A%20transparent%3B%20%20%20%20%20%20%20%20%20%20%20%20display%3A%20flex%3B%20%20%20%20%20%20%20%20%20%20%20%20justify-content%3A%20center%3B%20%20%20%20%20%20%20%20%20%20%20%20align-items%3A%20center%3B%20%20%20%20%20%20%20%20%20%20%20%20height%3A%20200px%3B%20%20%20%20%20%20%20%20%20%20%20%20margin%3A%200%3B%20%20%20%20%20%20%20%20%7D%20%20%20%20%20%20%20%20.layered-shadow-text%20%7B%20%20%20%20%20%20%20%20%20%20%20%20color%3A%20%23fff%3B%20%20%20%20%20%20%20%20%20%20%20%20font-weight%3A%20bold%3B%20%20%20%20%20%20%20%20%20%20%20%20font-family%3A%20%22Comic%20Sans%20MS%22%2C%20cursive%2C%20sans-serif%3B%20%20%20%20%20%20%20%20%20%20%20%20font-size%3A%2087px%3B%20%20%20%20%20%20%20%20%20%20%20%20text-align%3A%20center%3B%20%20%20%20%20%20%20%20%20%20%20%20animation%3A%20smoothPurpleStack%201s%20cubic-bezier(0%2C%200%2C%201%2C%201)%20infinite%20alternate%3B%20%20%20%20%20%20%20%20%7D%20%20%20%20%20%20%20%20%40keyframes%20smoothPurpleStack%20%7B%20%20%20%20%20%20%20%20%20%20%20%200%25%20%7B%20%20%20%20%20%20%20%20%20%20%20%20%20%20%20%20text-shadow%3A%20%20%20%20%20%20%20%20%20%20%20%20%20%20%20%20%20%20%20%205px%205px%200px%20%230075c9%2C%20%20%20%20%20%20%20%20%20%20%20%20%20%20%20%20%20%20%20%207.5px%207.5px%200px%20%230000e6%2C%20%20%20%20%20%20%20%20%20%20%20%20%20%20%20%20%20%20%20%2010px%2010px%200px%20%230b0070%3B%20%20%20%20%20%20%20%20%20%20%20%20%7D%20%20%20%20%20%20%20%20%20%20%20%2050%25%20%7B%20%20%20%20%20%20%20%20%20%20%20%20%20%20%20%20text-shadow%3A%20%20%20%20%20%20%20%20%20%20%20%20%20%20%20%20%20%20%20%200px%205px%200px%20%230075c9%2C%20%20%20%20%20%20%20%20%20%20%20%20%20%20%20%20%20%20%20%200px%207.5px%200px%20%230000e6%2C%20%20%20%20%20%20%20%20%20%20%20%20%20%20%20%20%20%20%20%200px%2010px%200px%20%230b0070%3B%20%20%20%20%20%20%20%20%20%20%20%20%7D%20%20%20%20%20%20%20%20%20%20%20%20100%25%20%7B%20%20%20%20%20%20%20%20%20%20%20%20%20%20%20%20text-shadow%3A%20%20%20%20%20%20%20%20%20%20%20%20%20%20%20%20%20%20%20%20-5px%205px%200px%20%230075c9%2C%20%20%20%20%20%20%20%20%20%20%20%20%20%20%20%20%20%20%20%20-7.5px%207.5px%200px%20%230000e6%2C%20%20%20%20%20%20%20%20%20%20%20%20%20%20%20%20%20%20%20%20-10px%2010px%200px%20%230b0070%3B%20%20%20%20%20%20%20%20%20%20%20%20%7D%20%20%20%20%20%20%20%20%7D%20%20%20%20%20%20%3C%2Fstyle%3E%3Cdiv%20class%3D%22container%22%3E%3Ch1%20class%3D%22layered-shadow-text%22%3EAltior%20Browser%3C%2Fh1%3E%3C%2Fdiv%3E%3C%2Fdiv%3E%3C%2FforeignObject%3E%3C%2Fsvg%3E)

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
