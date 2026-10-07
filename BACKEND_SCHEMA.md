# BACKEND SCHEMA — Connaissance transversale

> Ce dépôt est une **base de connaissances open source**, pas une application : les rubriques techniques (flux, schéma, design) décrivent ici l'organisation du contenu, les parcours de lecture et de contribution, et les conventions de rédaction.

## 1. Arborescence

```
connaissance_transversale/
├── notes/
│   ├── developpement/
│   ├── reseaux/
│   ├── cybersecurite/
│   ├── bases-de-donnees/
│   └── methodologie/
├── templates/fiche.md
├── CONTRIBUTING.md
└── README.md
```

## 2. Schéma de l'en-tête d'une fiche

```yaml
---
domaine: reseaux          # developpement | reseaux | cybersecurite | bases-de-donnees | methodologie
niveau: debutant          # debutant | intermediaire | avance
tags: [osi, protocoles]   # mots-clés libres, en minuscules
sources: ["https://…"]    # références consultées
---
```

| Champ | Type | Obligatoire | Règle |
|---|---|---|---|
| `domaine` | énumération | Oui | Correspond au dossier de la fiche |
| `niveau` | énumération | Oui | |
| `tags` | liste de chaînes | Non | Minuscules, sans accents de préférence |
| `sources` | liste d'URL ou de références | Oui dès qu'il y a un contenu repris | |

## 3. Nom de fichier

`notes/<domaine>/<Titre de la notion>.md` — le titre du fichier est celui utilisé dans les liens `[[…]]`.

## 4. Relations

Les liens `[[…]]` de la section « Voir aussi » forment le graphe de connaissances : chaque fiche doit en avoir au moins un.
