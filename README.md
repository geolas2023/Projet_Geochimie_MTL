# Projet Ines et Ismail

### GEO7531 — Géochimie de Montréal, Laval et de la Rive-Sud (CMM)

Carte web interactive des analyses géochimiques compilées sur l'île de Montréal, Laval et la Rive-Sud de la Communauté métropolitaine de Montréal :

- **Sédiments et sols** : sites analysés repérés dans EXAMINE, des thèses, des études d'impact (BAPE) et les données ouvertes de la Ville de Montréal.
- **Eau souterraine** : 695 analyses SIGÉOM (levés MRN 1978–1982).
- **Substrat rocheux** : 325 analyses SIGÉOM.
- **Eau de surface (île de Montréal)** : 179 stations du Réseau de suivi du milieu aquatique de la Ville de Montréal (RUISSO, COURDO) et 8 stations du suivi des métaux du MELCCFP.
- **Sols urbains** : 29 jardins communautaires analysés par la Direction de santé publique (2006–2009).
- **Sols — 9350 boul. de l'Acadie** : caractérisation SCP Environnement 2026 (6 forages, 14 échantillons 0–2,21 m ; 14 métaux, 30 HAP, C10–C50).
- **Publications GEOSCAN** pertinentes (liens).

**Carte :** https://geolas2023.github.io/Projet_Geochimie_MTL/

## Fichiers

| Fichier | Contenu |
|---|---|
| `index.html` | Carte web autonome (D3.js) |
| `donnees/BD_geochimie_CMM_GEO7531.xlsx` | Base de données : documents évalués, inventaire EXAMINE, sites, résultats par élément, eau, roche, GEOSCAN |
| `donnees/BD_geochimie_CMM_resultats_MTM8.xlsx` | Base consolidée : un résultat par ligne (20 256), coordonnées MTM zone 8 NAD83, méthode, source, emplacement dans la source et hyperliens |
| `donnees/geochimie_MTL_Laval.geojson` | Couche SIG (WGS84) des points de la phase 1 et des échantillons du 9350 boul. de l'Acadie |

## Sources

- MRNF, SIGÉOM — Géochimie, CSV « Échantillon sédiment » et « Échantillon roche sud » (version du 2026-11-14).
- MRNF, EXAMINE — fonds documentaire de Géologie Québec.
- MRNF, Découpages administratifs (SDA) — limites de la CMM et des municipalités.
- Ville de Montréal (limites terrestres ; sédiments, intercepteur sud-est) et Ville de Laval (districts) — CC-BY 4.0.
- SCP Environnement (2026), projet 15267 — certificat Eurofins EnvironeX 4711530 et plan géo-environnemental ; ORTAM (2025), rapports 18445 (ÉSE Phase I) et 18477 (géotechnique).
- RNCan, GEOSCAN / Dépôt ouvert des sciences et technologie.

## Mises en garde

- Unités des eaux SIGÉOM non fournies dans le CSV : mg/L présumé (à valider dans DV 84-15).
- Plusieurs localisations de sites sont approximatives (symboles creux sur la carte).
- Certaines valeurs extraites de tableaux PDF sont marquées « à vérifier » dans la base.
