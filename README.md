# Projet GEO7531 — Géochimie de Montréal, Laval et de la Rive-Sud (CMM)

Projet d'Ines et Ismael.

Carte web interactive des analyses géochimiques compilées sur l'île de Montréal, Laval et la Rive-Sud de la Communauté métropolitaine de Montréal :

- **Sédiments et sols** : sites analysés repérés dans EXAMINE, des thèses, des études d'impact (BAPE) et les données ouvertes de la Ville de Montréal.
- **Eau souterraine** : 695 analyses SIGÉOM (levés MRN 1978–1982).
- **Substrat rocheux** : 325 analyses SIGÉOM.
- **Publications GEOSCAN** pertinentes (liens).

**Carte :** https://geolas2023.github.io/Projet_Geochimie_MTL/

## Fichiers

| Fichier | Contenu |
|---|---|
| `index.html` | Carte web autonome (D3.js) |
| `donnees/BD_geochimie_CMM_GEO7531.xlsx` | Base de données : documents évalués, inventaire EXAMINE, sites, résultats par élément, eau, roche, GEOSCAN |
| `donnees/geochimie_MTL_Laval.geojson` | Couche SIG (WGS84) des points de la phase 1 |

## Sources

- MRNF, SIGÉOM — Géochimie, CSV « Échantillon sédiment » et « Échantillon roche sud » (version du 2026-11-14).
- MRNF, EXAMINE — fonds documentaire de Géologie Québec.
- MRNF, Découpages administratifs (SDA) — limites de la CMM et des municipalités.
- Ville de Montréal (limites terrestres ; sédiments, intercepteur sud-est) et Ville de Laval (districts) — CC-BY 4.0.
- RNCan, GEOSCAN / Dépôt ouvert des sciences et technologie.

## Mises en garde

- Unités des eaux SIGÉOM non fournies dans le CSV : mg/L présumé (à valider dans DV 84-15).
- Plusieurs localisations de sites sont approximatives (symboles creux sur la carte).
- Certaines valeurs extraites de tableaux PDF sont marquées « à vérifier » dans la base.
