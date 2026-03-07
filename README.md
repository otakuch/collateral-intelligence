# Collateral Intelligence AI Market Disruption Index

> **FR** · Tableau de bord d'intelligence financière qui cartographie l'impact des publications Anthropic/Claude sur les marchés publics secteur par secteur, événement par événement.

> **EN** · A financial intelligence dashboard mapping the market impact of Anthropic/Claude releases sector by sector, event by event.

---

![Version](https://img.shields.io/badge/version-3.0-blue?style=flat-square)
![Langue](https://img.shields.io/badge/langue-FR%20%2F%20EN-lightgrey?style=flat-square)
![License](https://img.shields.io/badge/license-CC%20BY--NC%204.0-green?style=flat-square)
![Status](https://img.shields.io/badge/status-actif-brightgreen?style=flat-square)
![GitHub Pages](https://img.shields.io/badge/GitHub%20Pages-déployé-orange?style=flat-square)

---

## 🇫🇷 Présentation

**Collateral Intelligence** est un outil d'analyse conçu pour suivre et visualiser les dommages collatéraux boursiers provoqués par les sorties de modèles Anthropic. Il croise données de marché, recherche académique et intelligence économique dans une interface bilingue FR/EN.

### Contexte

Chaque publication majeure de Claude (3.5 Sonnet, 3.7 Sonnet, Claude Code, Claude 4…) provoque des mouvements de marché mesurables : chutes sectorielles, repositionnements stratégiques, destruction de capitalisation. Ce tableau de bord documente ces événements en temps quasi-réel et les met en perspective avec les tendances longues.

### Ce que le dashboard fait

- **Suit les impacts confirmés** : événements de marché datés, sociétés affectées, sources primaires
- **Projette les prochaines cibles** : secteurs en ligne de mire selon les vecteurs de capacité connus
- **Identifie les gagnants** : investisseurs directs Anthropic, infrastructure, ETF à surveiller
- **Évalue la résilience** : indice d'adaptation par société (0–100, 3 dimensions)
- **Contextualise historiquement** : parallèles avec les vagues SaaS, mobile, streaming
- **Analyse réglementaire** : asymétrie EU AI Act vs. paysage américain
- **Intègre la recherche primaire Anthropic** : étude Massenkoff & McCrory (mars 2026) sur l'impact marché du travail

---

## 🇬🇧 Overview

**Collateral Intelligence** is an analytical tool tracking the collateral market damage caused by Anthropic model releases. It cross-references market data, academic research, and economic intelligence in a bilingual FR/EN interface.

### Context

Every major Claude release (3.5 Sonnet, 3.7 Sonnet, Claude Code, Claude 4…) triggers measurable market movements: sector sell-offs, strategic repositioning, market cap destruction. This dashboard documents these events in near real-time and frames them within longer-term trends.

### What the dashboard does

- **Tracks confirmed hits**: dated market events, affected companies, primary sources
- **Projects next targets**: sectors in the crosshairs based on known capability vectors
- **Identifies winners**: direct Anthropic equity investors, infrastructure plays, ETFs to watch
- **Scores resilience**: adaptation index per company (0–100, 3 dimensions)
- **Contextualizes historically**: parallels with SaaS, mobile, and streaming waves
- **Maps regulation**: EU AI Act vs. US landscape asymmetry
- **Integrates primary Anthropic research**: Massenkoff & McCrory study (March 2026) on labor market impact

---

## 📊 Onglets / Tabs

| # | FR | EN | Contenu |
|---|----|----|---------|
| 1 | Journal d'impact | Impact Log | Événements de marché confirmés · Graphique IGV |
| 2 | Prochaines cibles | Next Targets | 10 secteurs projetés · probabilité de disruption |
| 3 | Gagnants | Winners | Equity Anthropic · Infrastructure · ETF |
| 4 | Index d'adaptation | Adaptation Index | Radar résilience · classement par société |
| 5 | Patterns historiques | Historical Patterns | Disruptions passées · recherche Anthropic |
| 6 | Pare-feu réglementaire | Regulatory Firewall | EU AI Act · paysage US · tableau comparatif |
| 7 | Historique Claude | Claude History | Timeline des versions · impact cumulatif |
| 8 | Étude marché du travail | Labor Market Study | Massenkoff & McCrory · exposition observée |

---

## 🛠 Stack technique / Tech stack

```
HTML5 · CSS3 (variables, grid, flex) · JavaScript ES6+ vanilla
Sora + JetBrains Mono (Google Fonts)
SVG charts zero dependencies
Single-file architecture (no build step)
```

**Fonctionnalités interactives / Interactive features**

- Bascule langue FR ↔ EN
- Bascule devise USD ↔ EUR
- Thème clair / sombre
- Graphiques animés (SVG, staggered CSS)
- Radar d'adaptation dynamique
- Comparateur de sociétés (max 3)

---

## 🚀 Déploiement / Deployment

### Option 1 GitHub Pages (recommandé)

```bash
git clone https://github.com/otakuch/collateral-intelligence.git
cd collateral-intelligence
# Renommer le fichier principal
mv collateral-intelligence-v3.html index.html
# Push → GitHub Pages s'active automatiquement
```

Accès : `https://otakuch.github.io/collateral-intelligence`

### Option 2 Local

```bash
# Aucune dépendance, aucun serveur requis
open index.html   # macOS
start index.html  # Windows
```

### Option 3 Tout hébergeur statique

Compatible Netlify, Vercel, Cloudflare Pages glisser-déposer `index.html`.

---

## 📁 Structure du repo

```
collateral-intelligence/
├── index.html          # Dashboard complet (fichier unique)
├── README.md           # Ce fichier
└── LICENSE             # CC BY-NC 4.0
```

> Architecture monolithique intentionnelle : zéro dépendance, déploiement immédiat, offline-ready.

---

## 📰 Sources de données / Data sources

| Source | Usage |
|--------|-------|
| Goldman Sachs Research | Paniers short/long, capex hyperscalers |
| McKinsey State of AI 2025 | Projections adoption entreprise |
| WEF Future of Jobs 2025 | Déplacement d'emplois 2030 |
| Bloomberg / Reuters | Événements de marché datés |
| Anthropic Economic Index | Exposition observée par métier |
| Massenkoff & McCrory (2026) | [Labor Market Impacts of AI](https://www.anthropic.com/research/labor-market-impacts) |
| Eloundou et al. (2023) | Scores β faisabilité théorique LLM |
| BLS Employment Projections | Croissance emploi 2024–2034 |
| Statista / Gartner | Données adoption IA |
| @Brett_ETH | The Anthropic Playbook · Fév. 2026 |

> ⚠ Pas de conseil financier. Analyse uniquement. Vérifier toujours les sources primaires avant toute décision d'investissement.

---

## 🗂 Versions

| Version | Date | Changements |
|---------|------|-------------|
| v3.0 | Mars 2026 | Architecture multi-fichiers → monolithique · onglet Étude emploi · traduction FR complète · suppression AI Trend Radar |
| v2.0 | Fév. 2026 | 8 onglets · thème clair/dark · bascule devise |
| v1.0 | Jan. 2026 | Dashboard initial · 4 onglets |

---

## 👤 Auteur / Author

**Naully Nicolas**
Intelligence artificielle · Gouvernance · Cybersécurité · Réponse d'urgence

- 🌐 [naullynicolas.ch](https://naullynicolas.ch)
- 📧 sayhi@naullynicolas.ch
- 💼 [LinkedIn](https://www.linkedin.com/in/naully-nicolas)
- 🐙 [GitHub · otakuch](https://github.com/otakuch)

---

## 📄 Licence / License

**Creative Commons Attribution-NonCommercial 4.0 International (CC BY-NC 4.0)**

Libre d'utilisation, de partage et d'adaptation à des fins non commerciales, avec attribution.
Free to use, share, and adapt for non-commercial purposes, with attribution.

[![CC BY-NC 4.0](https://licensebuttons.net/l/by-nc/4.0/88x31.png)](https://creativecommons.org/licenses/by-nc/4.0/)

---

*Collateral Intelligence v3.0 · Mars 2026 · [otakuch.github.io/collateral-intelligence](https://otakuch.github.io/collateral-intelligence)*
