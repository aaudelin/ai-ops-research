# AI Ops — Veille Self-Healing Code

Veille technologique et business sur le **self-healing code** et les agents IA de maintenance applicative. Le dépôt centralise les rapports générés périodiquement à partir de sources publiques (web, Hacker News, Medium, Dev.to, GitHub, arXiv, blogs d'éditeurs, ProductHunt, InfoQ…).

## Structure

```
.
├── articles/   # Rapports de veille technique (synthèse + articles retenus)
└── trends/     # Rapports d'opportunités (tendances marché + leads / actions)
```

### `articles/` — Veille technique

Synthèse régulière (≈ quotidienne) des publications marquantes sur le self-healing code.

Chaque rapport contient :
- une **synthèse exécutive** des dynamiques du moment,
- les **points clés à retenir**,
- une sélection d'articles classés (Incontournables, recherche, retours d'expérience…),
- des liens directs vers les sources.

### `trends/` — Opportunités

Rapports hebdomadaires orientés business / freelance / SaaS.

Chaque rapport contient :
- un **résumé exécutif** du marché sur la fenêtre couverte,
- les **opportunités identifiées** (idée SaaS, prospect, partenariat, tendance, concurrence),
- un **scoring** (1 à 5 étoiles), le type de client cible et l'action suggérée,
- les sources et signaux datés.

## Convention de nommage

```
YYYY-MM-DD[_HH-MM]_<sujet>.md
```

Exemples : `2026-05-04_07-10_self-healing-code.md`, `2026-04-20_09-00_self-healing-code.md`.

La date encode la **date de génération** du rapport ; la fenêtre temporelle réellement couverte est précisée dans l'en-tête de chaque fichier.

## Lecture rapide

- Pour suivre l'état de l'art technique → dernier fichier de `articles/`.
- Pour repérer une opportunité commerciale ou un signal marché → dernier fichier de `trends/`.

## Langue

Tous les rapports sont rédigés en **français**.
