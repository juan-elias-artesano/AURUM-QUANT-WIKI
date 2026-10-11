# AURUM-QUANT-WIKI

Official user manuals (wikis) for **AURUM QUANT** cTrader indicators.
Every manual is a self-contained HTML page with screenshots — read it online or download it for offline use.

**🌐 Wiki hub (read online):** <https://juan-elias-artesano.github.io/AURUM-QUANT-WIKI/>

---

## Products

| Product | What it is | Read online | Download (ZIP) |
|---|---|---|---|
| **Advanced MACD Pro** | Adaptive multi-timeframe MACD & divergence engine — 10 MA kernels, regime-adaptive filter bank, A/B/C-graded divergences with a 13-component quality score, MTF confluence ladder, adaptive learning, info panel. 133 parameters, 11 outputs, `AccessRights.None`. | [manual.html](https://juan-elias-artesano.github.io/AURUM-QUANT-WIKI/Advanced%20MACD%20Pro/manual.html) | [⬇ Advanced-MACD-Pro-WIKI.zip](https://github.com/juan-elias-artesano/AURUM-QUANT-WIKI/raw/main/downloads/AURUM-QUANT-Advanced-MACD-Pro-WIKI.zip) |
| **Liquidity & Volume Nexus** | Professional chart overlay unifying market structure (BOS/CHoCH), liquidity sweeps and volume analysis — zones, watch board, session strip, result cards, signal journal. | [manual.html](https://juan-elias-artesano.github.io/AURUM-QUANT-WIKI/Liquidity%20and%20Volume%20Nexus/manual.html) | [⬇ Liquidity-and-Volume-Nexus-WIKI.zip](https://github.com/juan-elias-artesano/AURUM-QUANT-WIKI/raw/main/downloads/AURUM-QUANT-Liquidity-and-Volume-Nexus-WIKI.zip) |

> **Offline use:** download the ZIP for a product, unpack it and open `manual.html` in any browser.
> The archive is fully self-contained (HTML + `images/`) and needs no internet connection.
> Keep `manual.html` next to its `images/` folder.

You can also download **everything at once**:
[⬇ whole repository as ZIP](https://github.com/juan-elias-artesano/AURUM-QUANT-WIKI/archive/refs/heads/main.zip)

---

## Repository layout

```
AURUM-QUANT-WIKI/
├── index.html                        ← wiki hub (served by GitHub Pages)
├── README.md
├── downloads/                        ← ready-to-share offline archives
│   ├── AURUM-QUANT-Advanced-MACD-Pro-WIKI.zip
│   └── AURUM-QUANT-Liquidity-and-Volume-Nexus-WIKI.zip
├── Advanced MACD Pro/
│   ├── manual.html
│   └── images/
└── Liquidity and Volume Nexus/
    ├── manual.html
    └── images/
```

## Maintainer notes

- **Online reading** is powered by [GitHub Pages](https://pages.github.com/):
  *Settings → Pages → Source: “Deploy from a branch” → branch `main`, folder `/ (root)`*.
  The hub then lives at `https://juan-elias-artesano.github.io/AURUM-QUANT-WIKI/`
  and each manual at `…/<Product Folder>/manual.html`.
- **Adding a new product:** create a folder with `manual.html` + `images/`, add a card to
  `index.html`, a row to the table above, and (optionally) a per-product ZIP in `downloads/`.
- **Versioned downloads:** attach the ZIPs from `downloads/` to a
  [GitHub Release](https://github.com/juan-elias-artesano/AURUM-QUANT-WIKI/releases)
  if you want stable versioned links (e.g. `…/releases/download/v1.0/….zip`).

---

© 2026 AURUM QUANT. Trading involves substantial risk of loss. Documentation describes tooling, not investment advice.
