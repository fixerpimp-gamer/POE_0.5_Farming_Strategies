# PoE2 Farming Strategies — 0.5 Return of the Ancients

A community-driven, mobile-friendly reference for endgame farming strategies in **Path of Exile 2**, patch **0.5 (Return of the Ancients)**.

Browse 11 strategies (S/A tier) covering Abyss, Breach, Ritual, Expedition, Delirium, and more — each with tablet setups, Atlas tree priorities, master selections, and real profit breakdowns sourced from community guides and stream testing.

🔗 https://github.com/fixerpimp-gamer/POE_0.5_Farming_Strategies/edit/main/index.html

---

## ✨ Features

- **Sliding panel UI** — searchable, filterable strategy list (All / S Tier / A Tier / League / Meta)
- **Tabbed detail views** — Core Loop, Tablets, Atlas Tree, Drops, Results — broken down per strategy
- **Mobile-first** — dark fantasy aesthetic (Cinzel + Crimson Pro), fully responsive
- **No build step** — single static HTML file, works offline, no server required
- **JSON-backed** — all data lives in `poe2_farming_strategies.json` for easy editing/contribution

---

## 📂 Project Structure

```
.
├── index.html                      # Main UI (rename from poe2_farming_guide.html)
├── poe2_farming_strategies.json    # Source database — all strategy data
└── README.md
```

---

## 🗺️ Strategies Included (v0.1)

| Tier | Strategy | Highlights |
|------|----------|------------|
| **REQ** | Atlas Progression | Full quest line, tier/level map, master unlocks |
| **S** | Abyss | Currency, Diamond, Rogue Exile Reborn & Abyssal Eyes variants |
| **S** | Breach | Unstable Breach + Genesis Tree crafting |
| **A+** | Expedition | Verisium/Aldurs, Island Rumors, Saga priority |
| **A** | Ritual | Right of the Nameless, belt hunting, defer strategy |
| **A** | Ritual Farm v2 | Budget multi-mechanic (Ritual + Circles + Exiles) |
| **A** | Negative Rarity T16 | White base farming for crafters |
| **A** | Temple + Anomaly Maps | Atziri rotation, Lineage Support Gem hunting |
| **A** | Casual Atlas Exploration | Map crafting, ring flipping, traveling priority |
| **A** | Delirium Boss Rushing | Distilled Emotions, 200% fog, Simulacrum splinters |
| **A** | Boss Zone Rushing | Zero-investment Breach/King/Halls rushing (~20 div/hr) |

---

## 🚀 Hosting on GitHub Pages (Free)

1. Push this repo to GitHub
2. Go to **Settings → Pages**
3. Under "Source", select your branch (e.g. `main`) and root folder
4. Save — your site will be live at `https://<username>.github.io/<repo-name>/`

> If your main file isn't named `index.html`, rename `poe2_farming_guide.html` → `index.html` for it to load automatically.

---

## 🤝 Contributing

Found new strategy info, price updates, or corrections? PRs welcome!

- Strategy data lives in `poe2_farming_strategies.json`
- UI strategy cards are defined in the `STRATS` array inside `index.html`
- Keep tone/format consistent with existing entries (tablet setups, Atlas priorities, real results where possible)

---

## ⚠️ Disclaimer

Prices and drop rates reflect the PoE2 0.5 economy at time of writing and **will change** as the league progresses. Always check current market prices (e.g. via the in-game trade site or poe.ninja-style tools) before committing currency to a strategy.

---

## 📜 Version

**v0.1** — Initial public release. 11 strategies documented.
