# Yu-Gi-Oh Booster Pack & Card JSON Archive

This repository contains a complete JSON dataset of Yu-Gi-Oh! booster packs and the individual cards contained within each pack. The data was scraped directly from [Konami’s official card database](https://www.db.yugioh-card.com) and published here for archival and reference purposes.

## 📦 Contents

- `BoosterPackCardData.json`: A dictionary mapping each booster pack name to a list of card names.
- `PackNameUrlMap.json`: A dictionary mapping each booster pack name to its original Konami URL.

## 🧠 Purpose

Konami’s site does not offer a public API and is difficult to navigate programmatically. This dataset was created to preserve the full booster pack archive in a clean, structured format for developers, archivists, and fans.

There is **no code or tooling** included—this repository is purely a data archive.

## 🔍 Format

- Booster pack names are normalized and deduplicated (e.g. `"DarkBeginning1_2"`).
- Card data is stored as plain strings—no HTML, no metadata.
- All data is UTF-8 encoded and serialized using standard JSON formatting.

## ✅ Use Cases

- Reference booster pack contents without navigating Konami’s site
- Integrate into your own tools, apps, or datasets
- Preserve a snapshot of the Yu-Gi-Oh TCG booster pack history

## 📄 License

This dataset is provided as-is for educational and archival purposes. No affiliation with Konami or official Yu-Gi-Oh! entities.

---

