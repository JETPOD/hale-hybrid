# HALE-Hybrid v1.0.0

Calculateur d'espérance de vie en bonne santé combinant **capacités physiques fonctionnelles** (6 marqueurs) et **mode de vie / biomarqueurs sanguins** (variables avec HR mortalité > 1,5).

**Live** : https://jetpod.github.io/hale-hybrid/

## Marqueurs

### Capacités physiques (toggle skip individuels)
- A — VO2max (direct, Cooper, Step Test)
- B — Pompes max
- C — Force préhension (handgrip)
- D — Vitesse de marche
- E — Sit-to-Stand 30s
- F — Équilibre yeux fermés

### Mode de vie (toujours actif)
- Tabac · IMC · WHtR · Sommeil · Alcool · Activité physique

### Biomarqueurs (toggle "J'ai mes analyses")
- ApoB · hs-CRP · TA systolique

### Mode sportif (toggle public/pro)
- Back Squat 1RM relatif · Murph time

## Méthodologie
Score composite physique 0-100 pondéré selon l'âge (<60 vs ≥60), converti en ΔHALE en années, additionné aux modificateurs lifestyle/bio (rendements décroissants au-delà de 8 ans, plafond [-15, +12]).

Référence INSEE 2023 — EVSI à 65 ans : H 63,7 / F 64,1.

## Conçu par
[NutricellScience](https://nutricellscience.blog) · Signature Mark DOWN
